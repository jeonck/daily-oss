---
title: "SQLAlchemy 기반 멀티 DB 지원 파이썬 유틸리티 alchemy-utils 알파 출시"
date: 2026-08-13T23:23:31.196418+00:00
verdict: "백로그"
tags: ["python", "database", "cli"]
source: "https://simonwillison.net/2026/Aug/12/alchemy-utils/"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** Python 백엔드 데이터베이스 유틸리티 — sqlite-utils의 다중 DB 지원 버전으로 PostgreSQL·SQLite·DuckDB를 단일 API로 다루는 CLI/라이브러리
- **액션:** https://github.com/simonw/alchemy-utils 클론 후 uvx --with 'alchemy-utils[postgresql]' alchemy-utils rows '<db-url>' <table> 로컬 PostgreSQL 또는 SQLite DB에 실행해 insert/upsert 동작 확인
