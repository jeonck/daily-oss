---
title: "510바이트 MBR에서 실행되는 소형 언어 모델 — 부트 섹터 LLM 데모"
date: 2026-11-01T01:28:08.131476+00:00
verdict: "백로그"
tags: ["ai-llm", "systems-programming", "demo-scene"]
source: "https://github.com/kerlenton/bootgpt"
source_name: "HN (show hn)"
status: "대기"
---
- **근거:** AI/LLM + 시스템 프로그래밍 영역 — 510바이트 MBR 어셈블리로 구현된 char-level 신경망 추론 엔진으로, AI 경량 추론과 저수준 시스템 실험 모두에 해당
- **액션:** git clone https://github.com/kerlenton/bootgpt 후 QEMU로 부트 이미지 실행해(`qemu-system-x86_64 -drive format=raw,file=boot.img`) 가짜 Linux dmesg 무한 출력 확인
