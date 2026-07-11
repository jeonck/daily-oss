---
title: "Colibrì: 744B MoE 모델을 소비자 PC에서 디스크 스트리밍으로 구동하는 실험 도구"
date: 2026-07-11T22:40:01.275634+00:00
verdict: "백로그"
tags: ["llm-inference", "moe-offloading", "quantization"]
source: "https://github.com/JustVugg/colibri"
source_name: "HN (show hn)"
status: "대기"
---
- **근거:** AI/LLM 추론 최적화 영역 — 744B MoE 모델을 소비자 PC(RAM 32GB)에서 int4 + 전문가 디스크 스트리밍으로 구동하는 실험적 오픈소스 프로젝트
- **액션:** git clone https://github.com/JustVugg/colibri 후 README 확인, GLM 5.2 int4 로딩 방식 및 MoE 전문가 디스크 오프로딩 구현 코드 살펴보기
