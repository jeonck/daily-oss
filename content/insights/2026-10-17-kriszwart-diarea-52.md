---
title: "프론트엔드 보안 스캐너: 노출된 키·소스맵·API 맵 탐지 CLI + 크롬 확장"
date: 2026-10-17T00:46:19.617731+00:00
verdict: "즉시조치"
tags: ["frontend-security", "cli-tool", "secrets-detection"]
source: "https://github.com/kriszwart/diarea"
source_name: "GitHub Trending (topic:frontend)"
status: "대기"
---
- **근거:** 프론트엔드 보안 감사 도구 — 노출된 API 키, 소스맵, 디버그 글로벌 탐지용 CLI + Chrome 확장
- **액션:** npx diarea <your-site-url> 또는 git clone https://github.com/kriszwart/diarea && npm install && npm run build 후 CLI로 운영 사이트 스캔
