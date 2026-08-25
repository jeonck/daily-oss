---
title: "LLM 출력을 유발한 뉴런을 CLI로 추적하는 오픈소스 도구 NeuronScope"
date: 2026-08-25T23:03:46.960862+00:00
verdict: "백로그"
tags: ["llm-interpretability", "mcp-server", "cli"]
source: "https://dev.to/sourav-nandy/how-to-trace-which-neurons-actually-caused-your-llms-output-from-the-command-line-1ljp"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** LLM 내부 뉴런·어텐션 헤드를 CLI/MCP 서버로 추적하는 기계적 해석가능성 도구 — AI/LLM 관심 분야에 해당
- **액션:** pip install neuronscope-cli 후 `neuronscope trace gpt2 "The capital of France is"` 실행해 attention head 랭킹 출력 확인 (https://github.com/RudrenduPaul/neuronscope)
