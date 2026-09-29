---
title: "로컬 결정 모델 서빙 도구 Ollaya — Ollama의 decision model 버전"
date: 2026-09-29T02:18:34.305175+00:00
verdict: "즉시조치"
tags: ["ai-llm", "local-inference", "decision-models"]
source: "https://github.com/ollaya-dev/ollaya"
source_name: "GitHub Trending (stars:>200)"
status: "대기"
---
- **근거:** AI/LLM 관심 분야 — Ollama 방식의 로컬 decision model 서빙 도구로, NLI·GLiClass 등 분류/결정 모델을 TypeSafe 호환 API로 제공하는 신규 프레임워크
- **액션:** git clone https://github.com/ollaya-dev/ollaya && docker build -t ollaya . 후 laya 모델 pull하여 분류 추론 API 동작 확인
