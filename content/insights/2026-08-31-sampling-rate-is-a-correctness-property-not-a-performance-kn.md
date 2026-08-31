---
title: "샘플링 레이트는 성능 조절 값이 아니라 정확성 속성이다 — 광과민성 간질 검사 도구 개발 중 발생한 버그 사례"
date: 2026-08-31T00:49:58.954537+00:00
verdict: "학습"
tags: ["time-series", "windowed-sql", "clickhouse"]
source: "https://dev.to/edycutjong/sampling-rate-is-a-correctness-property-not-a-performance-knob-47p7"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** ClickHouse 윈도우 SQL과 시계열 샘플링 정확성에 대한 기술 블로그로, 백엔드/데이터 엔지니어링 영역에 해당하나 방송 영상 규제 준수라는 매우 좁은 도메인의 특수 도구 소개 글
- **액션:** 윈도우 함수에서 프레임 카운트 기반 경계 설정(fps-based window) 패턴을 자신의 시계열 쿼리에 적용할 수 있는지 검토
