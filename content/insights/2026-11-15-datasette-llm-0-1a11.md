---
title: "Datasette LLM 플러그인, OpenAI 호환 엔드포인트(Ollama·LM Studio) 지원 추가"
date: 2026-11-15T02:07:42.296986+00:00
verdict: "백로그"
tags: ["llm", "datasette", "ai-agent"]
source: "https://simonwillison.net/2026/Nov/14/datasette-llm/"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** LLM 프레임워크/AI 에이전트 관심 분야 — Datasette에 로컬 LLM(Ollama, LM Studio 등)을 붙여 데이터 분석 에이전트를 구성하는 플러그인
- **액션:** github.com/simonw/datasette-llm 클론 후 uvx --with datasette-agent datasette 명령으로 Ollama 연동 PoC 실행해보기
