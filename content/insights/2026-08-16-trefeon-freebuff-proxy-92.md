---
title: "FreeBuff 코딩 모델용 OpenAI 호환 셀프호스팅 게이트웨이"
date: 2026-08-16T22:56:22.064833+00:00
verdict: "백로그"
tags: ["ai-gateway", "openai-compatible", "self-hosted"]
source: "https://github.com/trefeon/freebuff-proxy"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** OpenAI 호환 API 게이트웨이로 AI/LLM 인프라 영역에 해당하며, Go 기반 실제 소스코드(cmd/, internal/, go.mod 등) 구조도 검증됨
- **액션:** git clone https://github.com/trefeon/freebuff-proxy && docker compose up -d 으로 로컬 실행 후 /v1/chat/completions 엔드포인트 및 어드민 대시보드 동작 확인
