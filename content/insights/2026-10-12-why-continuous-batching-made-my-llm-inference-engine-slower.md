---
title: "Continuous Batching이 LLM 추론 엔진을 오히려 느리게 만든 이유 — 커널 선택 분기 분석"
date: 2026-10-12T01:46:50.917053+00:00
verdict: "학습"
tags: ["llm-inference", "batching", "rust"]
source: "https://dev.to/lun0522/why-continuous-batching-made-my-llm-inference-engine-slower-3pjb"
source_name: "DEV Community - showdev"
status: "완료"
---
- **근거:** LLM 추론 최적화(continuous batching, GEMV vs GEMM 커널 선택) 기술 해설 — AI/LLM 관심 분야에 해당하는 심층 기사
- **액션:** mini-vllm-rs 저장소(https://github.com/lun0522/mini-vllm-rs) README 훑어보고, 배치 크기에 따른 Metal 커널 분기 로직 확인
