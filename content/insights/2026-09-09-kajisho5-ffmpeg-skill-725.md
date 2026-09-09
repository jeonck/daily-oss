---
title: "FFmpeg MCP 서버 — AI 에이전트에서 FFmpeg 기능을 직접 호출"
date: 2026-09-09T00:37:25.373198+00:00
verdict: "즉시조치"
tags: ["mcp-server", "ffmpeg", "ai-tool"]
source: "https://github.com/kajisho5/ffmpeg-skill"
source_name: "GitHub Trending (stars:>200)"
status: "대기"
---
- **근거:** FFmpeg 기능을 AI 에이전트에 연결하는 MCP 서버로, AI/LLM → MCP 서버 관심 분야에 직접 해당하며 스타 725개·실제 소스 구조(bin, mcp, evals, scripts, tests) 모두 확인됨
- **액션:** git clone https://github.com/kajisho5/ffmpeg-skill 후 mcp/ 디렉터리 확인 및 Claude Desktop 또는 MCP 호환 클라이언트에 연결해 FFmpeg 도구 호출 동작 확인
