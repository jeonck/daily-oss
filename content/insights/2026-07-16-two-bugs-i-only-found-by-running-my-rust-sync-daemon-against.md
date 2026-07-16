---
title: "Rust sync 데몬을 실 인프라에 연결하고서야 발견한 버그 두 가지"
date: 2026-07-16T22:51:28.188222+00:00
verdict: "학습"
tags: ["rust", "backend", "http-client"]
source: "https://dev.to/scripthpp/two-bugs-i-only-found-by-running-my-rust-sync-daemon-against-real-infrastructure-4278"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** Rust + reqwest HTTP 클라이언트의 리다이렉트 시 Authorization 헤더 자동 제거 동작 등 백엔드/개발 실무 인사이트를 담은 기술 블로그 글
- **액션:** reqwest 사용 시 scheme-change 리다이렉트에서 Authorization 헤더가 strip된다는 점을 숙지; 필요시 .redirect(Policy::custom(...))으로 명시적 처리 방식 확인
