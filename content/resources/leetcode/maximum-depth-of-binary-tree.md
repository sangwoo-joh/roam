---
layout: page
tags: [tree]
title: Maximum Depth of Binary Tree
---

관련 개념: [[Binary Tree]]

# [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)

 바이너리 트리의 루트가 주어졌을 때, 트리의 최대 깊이를 구하자. 트리의
 최대 깊이란 루트 노드로부터 가장 멀리 있는 리프 노드까지 가는 경로의
 길이와 같다. 노드의 개수 범위는 0~10,000이다.


## 재귀적으로 구하기

 [[Binary Tree|이진 트리 개념]]을 참조하면 좋다.

 트리의 깊이는 다음과 같이 재귀적으로 정의된다.
 1. 노드가 null 이면 0
 2. 노드가 null이 아니라면, 왼쪽 서브트리와 오른쪽 서브트리의 깊이 중
    더 큰 값 + 1

```python
def maxDepth(root):
    def height(node):
        if node is None:
            return 0
        else:
            return max(height(node.left), height(node.right)) + 1
    return height(root)
```
