---
title: "lobste.rs, MariaDB에서 SQLite로 마이그레이션 완료 — 단일 VPS에서 비용 절반"
date: 2026-07-14T22:50:14.711965+00:00
verdict: "학습"
tags: ["sqlite", "backend", "database-migration"]
source: "https://simonwillison.net/2026/Jul/14/lobsters-sqlite/#atom-everything"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** SQLite를 프로덕션 Rails 앱에 적용한 실제 마이그레이션 사례로, 백엔드/인프라 아키텍처 관심 분야에 해당
- **액션:** Simon Willison 글과 Lobsters PR(github.com/lobsters/lobsters/pull/1935)을 읽고 SQLite 프로덕션 운용 패턴(멀티 DB 파일 분리, Litestream 등) 정리
