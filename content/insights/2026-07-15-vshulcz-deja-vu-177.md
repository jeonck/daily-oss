---
title: "코딩 에이전트용 오픈소스 메모리 레이어 — Claude Code·Codex 세션 로그 기반 MCP 연동"
date: 2026-07-15T22:52:00.874809+00:00
verdict: "즉시조치"
tags: ["ai-coding-tools", "mcp", "memory-layer"]
source: "https://github.com/vshulcz/deja-vu"
source_name: "GitHub Trending (topic:developer-tools)"
status: "대기"
---
- **근거:** AI 코딩 도구(Claude Code·Codex·opencode) 세션 로그를 재활용해 메모리 검색·MCP recall·시크릿 자동 삭제를 제공하는 Go 단일 바이너리 — AI/LLM + AI 코딩 도구 영역에 직접 해당
- **액션:** `bash <(curl -sL https://raw.githubusercontent.com/vshulcz/deja-vu/main/install.sh)` 로 설치 후 `deja-vu mcp` 명령으로 Claude Code MCP 연동 테스트 및 기존 세션 로그 메모리 검색 확인
