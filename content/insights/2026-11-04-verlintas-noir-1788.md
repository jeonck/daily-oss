---
title: "ADB로 Android 앱 프라이버시·권한·엔드포인트 감사하는 CLI 도구 NOIR"
date: 2026-11-04T02:42:08.226943+00:00
verdict: "즉시조치"
tags: ["android-security", "privacy-audit", "developer-tools"]
source: "https://github.com/Verlintas/NOIR"
source_name: "GitHub Trending (stars:>200)"
status: "대기"
---
- **근거:** 개발자 도구(CLI) + 보안/프라이버시 감사 영역 — Kotlin 기반 ADB Android 앱 권한·엔드포인트·데이터 흐름 분석 도구로, 실제 소스 구조(cli/, core/, Gradle) 확인됨, 1788★/140포크로 완성도 높음
- **액션:** git clone https://github.com/Verlintas/NOIR && cd NOIR && ./gradlew :cli:installDist 후 Android 에뮬레이터 or 실기기 연결해 `./noir audit <패키지명>` 실행으로 권한·아웃바운드 엔드포인트 리포트 확인
