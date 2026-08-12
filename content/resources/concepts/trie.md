---
title: Trie
---

트라이는 문자열의 접두사를 경로로 공유하는 트리다. 단어 존재 여부뿐 아니라 특정 접두사로 시작하는 모든 단어를 탐색해야 할 때 유용하다.

## 구현 요점

- 각 노드는 다음 문자에서 자식 노드로 가는 [[Hash Table]]을 가진다.
- 단어가 끝나는 지점을 별도로 표시한다.
- 와일드카드가 있으면 가능한 자식을 따라 [[Backtracking]]한다.

## 대표 문제

- [[Implement Trie]]
- [[Design Search Autocomplete System]]
- [[Word Search]]
