---
title: "OpenRouter 자동 라우팅의 함정과 공급자 직접 지정 방법"
date: 2026-09-12T00:37:59.168939+00:00
verdict: "학습"
tags: ["llm", "ai-infra", "openrouter"]
source: "https://simonwillison.net/2026/Sep/11/so-you-want-to-use-openrouter/"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** LLM API 라우팅 도구(OpenRouter) 사용 시 주의사항을 다루는 AI/LLM 분야 기술 해설 기사
- **액션:** OpenRouter를 사용하는 프로젝트에서 `provider.only` 옵션과 `/endpoints` API로 라우팅 공급자를 명시적으로 고정하는 방식을 검토
