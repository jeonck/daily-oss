---
title: "AI 평가 스코어러의 오탐 — 오답이 정답을 언급하기만 해도 통과되는 패턴 분석"
date: 2026-10-17T00:46:19.617731+00:00
verdict: "학습"
tags: ["ai-evaluation", "llm", "inspect-ai"]
source: "https://dev.to/agentdev9/two-eval-scorers-passed-a-wrong-answer-because-it-mentioned-the-right-one-10c7"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** AI/LLM 평가(eval) 프레임워크의 스코어러 오탐 패턴을 분석한 기술 블로그 글로, AI 에이전트·LLM 평가 도구 관심 분야에 해당
- **액션:** Inspect AI, promptfoo 등 eval 프레임워크 사용 시 deterministic scorer의 false-positive 패턴(정답 언급만으로 통과) 을 인지하고, 직접 BoolQ 스타일 테스트로 재현해보기
