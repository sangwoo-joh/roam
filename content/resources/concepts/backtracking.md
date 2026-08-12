---
title: Backtracking
---

백트래킹은 선택을 하나 추가하고 재귀적으로 탐색한 뒤 그 선택을 되돌리는 방식이다. 가능한 모든 조합을 보되, 정답이 될 수 없는 상태는 일찍 중단한다.

## 구현 요점

- 재귀 호출 전후에 상태를 정확히 추가하고 복구한다.
- 같은 상태를 반복하면 메모이제이션이나 [[Dynamic Programming]]을 검토한다.
- 후보 순서를 고정하면 중복 조합을 줄일 수 있다.

## 대표 문제

- [[Combination Sum]]
- [[Matchsticks to Square]]
- [[Word Search]]
