---
title: String
---

문자열 문제는 배열 순회 기법을 그대로 사용하는 경우가 많지만, 문자 빈도와 접두사·접미사, 부분 문자열, 파싱 규칙을 함께 고려해야 한다.

## 팰린드롬

양 끝 문자를 비교할 때는 [[Two Pointers]]를 사용한다. 모든 부분 팰린드롬을 찾을 때는 각 위치를 중심으로 양쪽으로 확장하는 방법이 단순하다.

## 정규 표현식

정규 표현식은 문자열을 토큰으로 나누거나 일정한 패턴을 검증할 때 유용하다. 중첩된 문법 자체를 평가해야 한다면 정규 표현식보다 [[Stack]]이나 별도의 파서가 더 적합하다.

## 대표 문제

- [[Longest Substring Without Repeating Characters]]
- [[Valid Palindrome]]
- [[Palindromic Substrings]]
