---
title: "PHP 쉘 인젝션 취약점 탐지기 — openai/php2shell-checker"
date: 2026-10-25T00:31:53.982398+00:00
verdict: "백로그"
tags: ["developer-tool", "security", "static-analysis"]
source: "https://github.com/openai/php2shell-checker"
source_name: "GitHub Trending (stars:>200)"
status: "대기"
---
- **근거:** PHP 코드의 쉘 인젝션 취약점을 탐지하는 JavaScript 기반 정적 분석 도구 — 개발자 도구/보안 카테고리에 해당
- **액션:** git clone https://github.com/openai/php2shell-checker && node phpcheck.js 로 샘플 PHP 파일 대상 취약점 탐지 동작 확인
