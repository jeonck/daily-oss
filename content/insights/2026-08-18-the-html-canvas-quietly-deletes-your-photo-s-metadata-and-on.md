---
title: "HTML canvas는 이미지 메타데이터(EXIF/GPS)를 자동 삭제한다 — 프론트엔드 함정 정리"
date: 2026-08-18T23:00:46.878002+00:00
verdict: "학습"
tags: ["frontend", "canvas", "image-metadata"]
source: "https://dev.to/bellsal_b44bf6d/the-html-canvas-quietly-deletes-your-photos-metadata-and-one-day-that-bites-you-2h68"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** 프론트엔드/웹 개발 영역 — HTML canvas의 EXIF 메타데이터 손실 동작을 설명하는 기술 아티클
- **액션:** 브라우저 이미지 처리 시 exifr 라이브러리로 canvas 통과 전 메타데이터를 미리 추출·보존하는 패턴 메모해두기
