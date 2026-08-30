---
title: "DGX Spark 2노드에서 DeepSeek/Qwen 서빙 + QLoRA 파인튜닝 자체 호스팅 구성"
date: 2026-08-30T00:42:32.474724+00:00
verdict: "백로그"
tags: ["ai-llm", "self-hosted", "vllm"]
source: "https://github.com/zorost/sparkduet"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** AI/LLM 관심 분야 — DeepSeek·Qwen 자체 호스팅 추론(vLLM TP=2)과 Unsloth QLoRA 파인튜닝을 NVIDIA DGX Spark 위에서 구성하는 실전 레포
- **액션:** git clone https://github.com/zorost/sparkduet 후 configs/ 및 finetune/ 구조와 install.sh를 읽어 DGX Spark 없이도 단일 GPU 환경에 적용 가능한 설정 패턴 파악
