---
title: "Rust 컴파일러 데몬 ra-jit — 빠른 증분 빌드 및 실행 중 코드 핫패치"
date: 2026-10-21T00:56:51.911644+00:00
verdict: "즉시조치"
tags: ["rust", "developer-tools", "build-tools"]
source: "https://github.com/indexable-inc/ra-jit"
source_name: "GitHub Trending (topic:developer-tools)"
status: "대기"
---
- **근거:** Rust 빌드 데몬 + 실행 중 코드 핫패치(live edit) 기능을 제공하는 개발자 도구로, 개발 생산성 도구 관심 분야에 직접 해당
- **액션:** nix run github:indexable-inc/ra-jit 로 기존 Cargo 프로젝트에서 실행해 증분 빌드 속도와 live edit 동작 확인
