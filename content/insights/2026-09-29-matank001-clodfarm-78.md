---
title: "Claude Code 에이전트 팜 — 미션 하나로 다수 서브에이전트 병렬 실행 및 사용량 자동 페이싱"
date: 2026-09-29T02:18:34.305175+00:00
verdict: "즉시조치"
tags: ["ai-agents", "claude-code", "self-hosted"]
source: "https://github.com/matank001/clodfarm"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** Claude Code 에이전트를 복수로 병렬 운영·속도 조절하는 AI 에이전트 오케스트레이터 — AI 에이전트/코딩 도구 관심 분야에 직접 해당
- **액션:** git clone https://github.com/matank001/clodfarm && cp .env.example .env 후 docker-compose up 으로 로컬 실행, 간단한 미션 하나 plant해서 sub-agent 분기 동작 확인
