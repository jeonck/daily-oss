---
title: "AI 에이전트용 PostgreSQL 인텔리전스 MCP 서버 — pgbot"
date: 2026-08-17T23:00:02.939013+00:00
verdict: "즉시조치"
tags: ["mcp-server", "ai-agent", "postgresql"]
source: "https://github.com/pgrundev/pgbot"
source_name: "GitHub Trending (topic:ai)"
status: "대기"
---
- **근거:** AI 에이전트를 위한 PostgreSQL MCP 서버 — .mcp.json·.claude-plugin 포함으로 Claude/AI 에이전트와 즉시 연동 가능하며, AI/LLM + 백엔드/데이터베이스 관심 분야에 정확히 해당
- **액션:** git clone https://github.com/pgrundev/pgbot && ./install.sh 또는 docker-compose.test.yml로 로컬 실행 후 .mcp.json을 Claude에 연결해 PostgreSQL 스키마 질의 PoC 확인
