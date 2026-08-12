---
title: Interval Algorithms
---

구간 문제는 시작점과 끝점의 관계를 다룬다. 먼저 어느 끝점을 기준으로 [[Sorting|정렬]]할지 정하면 겹침, 병합, 선택 문제를 순차적으로 처리할 수 있다.

## 대표 패턴

- 병합은 시작점 순서로 보면서 현재 끝점을 확장한다.
- 겹치지 않는 구간을 최대한 선택할 때는 끝점이 빠른 구간부터 고른다.
- 동시에 열려 있는 구간 수를 세면 [[Heap]]이나 스위프 라인을 사용한다.

## 대표 문제

- [[Merge Intervals]]
- [[Insert Interval]]
- [[Non-overlapping Intervals]]
- [[Meeting Rooms]]
