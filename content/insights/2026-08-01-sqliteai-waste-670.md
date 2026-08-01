---
title: "RAM 초과 LLM을 NVMe 스트리밍으로 실행하는 의존성 없는 C 추론 엔진"
date: 2026-08-01T23:39:29.747022+00:00
verdict: "즉시조치"
tags: ["llm-inference", "ai-optimization", "local-llm"]
source: "https://github.com/sqliteai/waste"
source_name: "GitHub Trending (stars:>200)"
status: "대기"
---
- **근거:** AI/LLM 추론 최적화 — NVMe 스트리밍으로 RAM 초과 대형 모델(Kimi K3 2.78조 파라미터) 로컬 실행을 가능하게 하는 C 추론 엔진
- **액션:** git clone https://github.com/sqliteai/waste && make 빌드 후 소형 모델로 NVMe 스트리밍 추론 동작 확인
