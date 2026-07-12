---
title: "Grok Build → Claude Code/OpenAI 호환 자체 호스팅 프록시"
date: 2026-07-12T22:40:20.488277+00:00
verdict: "백로그"
tags: ["ai-llm", "self-hosted", "proxy"]
source: "https://github.com/GreyGunG/grokbuild-proxy"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** AI/LLM 카테고리 — Grok Build를 Claude Code / OpenAI 호환 API로 변환하는 로컬 자체 호스팅 프록시로, LLM 비용 절감 및 대안 모델 활용에 해당
- **액션:** git clone https://github.com/GreyGunG/grokbuild-proxy && docker-compose up -d 로 로컬 실행 후 Claude Code의 API base URL을 프록시 엔드포인트로 변경해 Grok 모델 경유 동작 확인
