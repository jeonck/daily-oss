---
title: "Claude Code Opus 5 Auto Mode, 80% 성공률 프롬프트 인젝션 공격에 뚫림"
date: 2026-08-28T06:21:11.073328+00:00
verdict: "학습"
tags: ["ai-agent-security", "prompt-injection", "claude-code"]
source: "https://simonwillison.net/2026/Aug/27/breaking-claude-code-opus-5-auto-mode/"
source_name: "Simon Willison"
status: "완료"
---
- **근거:** AI 에이전트(Claude Code) 프롬프트 인젝션 공격 취약점 연구 — AI/LLM 에이전트 보안 영역
- **액션:** Claude Code나 유사 코딩 에이전트를 사용할 때 샌드박스(컨테이너/VM) 격리, 네트워크 egress 제한, 홈 디렉터리·SSH키·클라우드 크리덴셜 미노출 여부 점검
