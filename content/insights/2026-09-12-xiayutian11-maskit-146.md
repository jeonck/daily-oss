---
title: "LLM 요청 자동 마스킹 로컬 프라이버시 게이트웨이 — Claude Code·Cursor 지원"
date: 2026-09-12T00:37:59.168939+00:00
verdict: "즉시조치"
tags: ["ai-privacy", "llm-gateway", "data-masking"]
source: "https://github.com/xiaYuTian11/maskit"
source_name: "GitHub Trending (topic:llm)"
status: "대기"
---
- **근거:** AI/LLM 범주 — Cursor·Claude Code 등 AI 코딩 도구의 LLM 요청에서 민감 데이터를 로컬에서 자동 마스킹하고 응답 스트림에서 복원하는 프라이버시 게이트웨이
- **액션:** git clone https://github.com/xiaYuTian11/maskit && docker-compose up 으로 로컬 게이트웨이 기동 후 Claude Code 또는 Cursor의 Base URL을 localhost로 교체해 마스킹 동작 확인
