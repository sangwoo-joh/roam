---
title: Disjoint Set
---

서로소 집합은 원소들이 어느 연결 요소에 속하는지 관리한다. `find`로 대표 원소를 찾고 `union`으로 두 집합을 합친다.

## 최적화

- 경로 압축은 `find` 중 만난 노드가 대표 원소를 직접 가리키게 한다.
- 랭크나 크기 기준 합치기는 작은 트리를 큰 트리 아래에 붙인다.

무향 그래프의 연결 요소 개수와 사이클 판별에 특히 유용하며 [[Graph Algorithms]]와 밀접하다.

## 대표 문제

- [[Number of Islands]]
- [[Graph Valid Tree]]
- [[Number of Connected Components in an Undirected Graph]]
