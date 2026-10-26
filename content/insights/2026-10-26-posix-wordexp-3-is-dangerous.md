---
title: "POSIX wordexp(3) 함수의 보안 위험성"
date: 2026-10-26T00:43:16.797426+00:00
verdict: "학습"
tags: ["security", "posix", "system-programming"]
source: "https://yossarian.net/til/post/posix-wordexp-3-is-dangerous/"
source_name: "Lobsters"
status: "대기"
---
- **근거:** 시스템 프로그래밍/보안 관련 POSIX API 취약점 — 개발자 도구/백엔드 안전 코딩 관심 분야에 해당
- **액션:** 블로그 글 읽고 wordexp(3) 함수의 쉘 인젝션 위험성과 안전한 대안(exec 계열 사용 등) 파악하기
