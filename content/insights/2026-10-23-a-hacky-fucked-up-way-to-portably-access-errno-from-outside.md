---
title: "C 외부에서 errno에 이식 가능하게 접근하는 비정통적 방법"
date: 2026-10-23T00:56:19.508991+00:00
verdict: "학습"
tags: ["systems-programming", "c-internals", "low-level"]
source: "https://sebsite.pw/w/20260925-errno.html"
source_name: "Lobsters"
status: "대기"
---
- **근거:** C 런타임 내부 구조(errno 접근 방식)를 다루는 시스템 프로그래밍 기술 아티클 — 개발자 도구/언어 지식 범주에 해당
- **액션:** 아티클 읽고 errno의 thread-local 저장 방식 및 플랫폼별 심볼 노출 차이 파악
