---
title: Binary Search
---

이분 탐색은 정렬된 탐색 공간을 절반씩 버리는 기법이다. 단순히 값을 찾는 것뿐 아니라 조건을 처음 또는 마지막으로 만족하는 경계를 찾는 데 더 자주 쓰인다.

## 경계 찾기

`lower bound`는 조건을 만족하는 첫 위치, `upper bound`는 조건을 만족하지 않기 시작하는 첫 위치로 생각하면 구현하기 쉽다. 루프가 끝난 뒤 반환할 인덱스의 의미를 먼저 정해야 한다.

## 회전된 정렬 배열

중앙값과 양 끝을 비교해 어느 절반이 정렬되어 있는지 판단한 다음, 목표가 포함될 수 없는 절반을 버린다.

## 대표 문제

- [[Find Minimum in Rotated Sorted Array]]
- [[Search in Rotated Sorted Array]]
- [[Snapshot Array]]
