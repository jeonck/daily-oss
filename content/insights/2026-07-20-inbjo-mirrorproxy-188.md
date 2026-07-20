---
title: "Rust 기반 올인원 패키지 미러 가속 프록시 — MirrorProxy"
date: 2026-07-20T23:39:04.945726+00:00
verdict: "백로그"
tags: ["self-hosted", "mirror-proxy", "devops"]
source: "https://github.com/inbjo/MirrorProxy"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** DevOps/인프라 분야의 셀프호스팅 미러 가속 프록시 — GitHub·Docker·npm·PyPI·Cargo·Go 모듈 등 주요 패키지 레지스트리를 단일 어댑터 기반으로 통합 지원
- **액션:** git clone https://github.com/inbjo/MirrorProxy && docker compose -f compose.yaml up -d 로 로컬 구동 후 config.example.toml 기반으로 Docker/PyPI 미러 설정 PoC 확인
