---
title: "macOS 전체 디스크 파일 검색 CLI — 800만 파일 1ms 퍼지 검색"
date: 2026-10-11T01:14:45.373267+00:00
verdict: "백로그"
tags: ["cli", "rust", "developer-tools"]
source: "https://github.com/noahdunnagan/fsearch"
source_name: "GitHub Trending (stars:>200)"
status: "대기"
---
- **근거:** 개발자 도구 — Rust로 구현된 macOS 전체 디스크 파일 검색 CLI 도구(퍼지 검색, 타이포 허용, 인덱싱 기반 content grep)
- **액션:** git clone https://github.com/noahdunnagan/fsearch && cargo build --release 후 대용량 디렉토리에서 fd/ripgrep 대비 검색 속도 비교 테스트
