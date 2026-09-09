---
title: "런타임에 도구를 스스로 만들고 사용자 승인 후 실행하는 거버넌스 AI 에이전트 'Systemu'"
date: 2026-09-09T00:37:25.373198+00:00
verdict: "백로그"
tags: ["ai-agent", "tool-forging", "llm-framework"]
source: "https://dev.to/rameswaran_mohan_9c8b5d8f/i-built-an-ai-agent-that-forges-its-own-tools-mid-task-and-asks-first-open-source-60-second-1989"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** AI 에이전트 관심 분야 — 에이전트가 부족한 도구를 런타임에 자체 생성하고 사용자 승인을 거쳐 실행하는 governed self-provisioning 패턴이 독특한 로컬 우선 AI 에이전트 런타임
- **액션:** pip install 'systemu[dashboard]' && systemu init && systemu start 로 로컬 Ollama 연결 후 간단한 파일 처리 태스크를 에이전트에 할당해 Tool Forging + 거버넌스 플로우 직접 확인
