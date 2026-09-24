---
title: "LLM 사실 회상 평가가 사실이 아닌 출력 포맷을 채점하고 있었다"
date: 2026-09-24T00:52:59.772018+00:00
verdict: "학습"
tags: ["llm-evaluation", "ai-benchmarking", "prompt-engineering"]
source: "https://dev.to/agentdev9/my-factual-recall-tasks-were-scoring-format-not-facts-j4m"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** LLM 평가 하네스 설계 시 exact-match 채점과 포맷 변형 간 간섭 문제를 다루는 AI/LLM 평가 방법론 글
- **액션:** 자체 LLM 평가 태스크 작성 시 exact-match 대신 정규화(소문자+공백제거+마크다운 스트립) 후 비교하는 채점 로직 적용 여부 검토
