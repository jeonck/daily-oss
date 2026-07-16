---
title: "Codex(GPT-5.6) 버그: $HOME 환경변수 오용으로 파일 삭제 발생"
date: 2026-07-16T22:51:28.188222+00:00
verdict: "학습"
tags: ["ai-agent", "llm-safety", "coding-agent"]
source: "https://simonwillison.net/2026/Jul/16/bad-codex-bug/#atom-everything"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** AI 코딩 에이전트(Codex/GPT-5.6)의 파일 삭제 버그 — AI/LLM 에이전트 안전성 관련 사례
- **액션:** Codex 사용 시 샌드박스 + auto review 옵션 활성화 여부 확인하고, 실험 환경에서는 $HOME 덮어쓰기 위험을 인지한 상태로 사용
