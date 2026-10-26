---
title: "추론 시점 에이블리터레이션 적용 llama.cpp 포크"
date: 2026-10-26T00:43:16.797426+00:00
verdict: "백로그"
tags: ["llm-inference", "abliteration", "llama-cpp"]
source: "https://github.com/heterodoxin/AbliteratedOutTheBox"
source_name: "GitHub Trending (topic:ai)"
status: "대기"
---
- **근거:** AI/LLM 추론 최적화 영역 — llama.cpp를 포크해 모델 가중치 수정 없이 추론 시점에 abliteration(안전장치 제거)을 적용하는 실험적 도구
- **액션:** git clone https://github.com/heterodoxin/AbliteratedOutTheBox && cmake -B build && cmake --build build -j$(nproc) 로 빌드 확인 후, 로컬 GGUF 모델로 abliteration 파라미터 효과 비교 테스트
