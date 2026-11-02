---
title: "바이템포럴 AI 메모리 시스템 — 시간 기반 감쇠·TTL·MCP 서버 지원 (Neo4j + PostgreSQL + Redis)"
date: 2026-11-02T01:49:04.069134+00:00
verdict: "백로그"
tags: ["ai-memory", "mcp-server", "graph-db"]
source: "https://github.com/gh9ko8y/graphmemory"
source_name: "GitHub Trending (topic:ai)"
status: "대기"
---
- **근거:** AI / LLM 영역 — MCP 서버 탑재 바이템포럴 AI 메모리 시스템으로, LLM 에이전트 기억 계층 구현에 직접 활용 가능
- **액션:** git clone https://github.com/gh9ko8y/graphmemory 후 docker-compose up으로 로컬 스택 기동, mcp_server.py를 Claude/Cursor 등 MCP 호환 클라이언트에 연결해 recall/decay 동작 확인
