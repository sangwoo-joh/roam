---
title: Dynamic Programming
---

동적 계획법은 겹치는 부분 문제의 답을 저장해 중복 계산을 피한다. 상태가 무엇을 의미하는지, 한 상태가 어떤 이전 상태에서 오는지, 계산 순서가 무엇인지를 먼저 정의해야 한다.

## 접근 순서

1. 재귀식으로 상태와 전이를 적는다.
2. 종료 조건을 정한다.
3. 메모이제이션을 적용하거나 의존 순서대로 테이블을 채운다.
4. 이전 상태 일부만 필요하면 공간을 줄인다.

## 대표 문제

- [[Climbing Stairs]]
- [[Longest Common Subsequence]]
- [[Coin Change]]
- [[Maximum Subarray]]
