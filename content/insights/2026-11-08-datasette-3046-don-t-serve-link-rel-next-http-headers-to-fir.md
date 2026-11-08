---
title: "Firefox의 link: rel=next 프리페치 문제 — Datasette 버그픽스 사례"
date: 2026-11-08T01:49:31.898315+00:00
verdict: "학습"
tags: ["http-headers", "browser-behavior", "datasette"]
source: "https://simonwillison.net/2026/Nov/7/link-rel-next/"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** HTTP link 헤더와 브라우저 프리페치 동작에 관한 기술적 인사이트 — 웹 백엔드 일반 지식
- **액션:** 자체 웹 앱의 HTTP 응답 헤더에 rel=next가 포함되어 있는지 확인 (curl -I <url> | grep -i link)
