---
title: Simulation
---

시뮬레이션은 문제에 주어진 상태 변화 규칙을 그대로 구현한다. 알고리즘 자체보다 상태 표현, 한 단계의 갱신 순서, 반복되는 상태를 감지하는 방법이 중요하다.

## 문제에서 보는 신호

- 다음 상태가 현재 상태에만 의존한다.
- 단계 수가 매우 크면 이전 상태를 [[Hash Table|해시 테이블]]에 기록해 사이클을 찾는다.
- 여러 객체를 동시에 움직이면 한 단계의 읽기와 쓰기를 분리한다.

## 대표 문제

- [[Prison Cells After N Days]]
- [[Walking Robot Simulation]]
- [[Text Justification]]
