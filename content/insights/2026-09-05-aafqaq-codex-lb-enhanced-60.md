---
title: "Codex 호환 계정 풀 게이트웨이 — failover·세션 복구·관측성 내장 셀프호스팅 프록시"
date: 2026-09-05T00:23:14.787031+00:00
verdict: "백로그"
tags: ["llm-gateway", "self-hosted", "ai-infra"]
source: "https://github.com/aafqaq/codex-lb-enhanced"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** AI/LLM 인프라 — Codex 호환 API 계정 풀 게이트웨이로, 복수 계정 failover·세션 복구·관측성을 제공하는 셀프호스팅 LLM 프록시 도구
- **액션:** git clone https://github.com/aafqaq/codex-lb-enhanced && docker-compose up -d 로 로컬에서 올려 .env.example 기반 계정 풀 구성 및 /health 엔드포인트 동작 확인
