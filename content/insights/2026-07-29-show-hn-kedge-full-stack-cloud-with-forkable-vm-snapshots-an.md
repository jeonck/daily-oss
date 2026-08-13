---
title: "Kedge – VM 스냅샷 포크 + 글로벌 SQLite 복제 기반 상태유지 서버리스 플랫폼"
date: 2026-07-29T23:40:47.608263+00:00
verdict: "학습"
tags: ["serverless", "sqlite-replication", "cloud-infra"]
source: "https://kedge.dev/"
source_name: "HN (show hn)"
status: "완료"
---
- **근거:** DevOps/클라우드 인프라 영역 — Fly.io 출신이 만든 글로벌 상태유지 서버리스 플랫폼이나, kedge.dev는 상용 SaaS이고 오픈소스 핵심은 CRDT 기반 SQLite 복제 라이브러리(syzy)에 한정됨
- **액션:** https://github.com/wjordan/syzy 레포 훑어보며 CRDT 기반 멀티라이터 SQLite 복제 구조 파악 (Litestream·Corrosion 대비 차이점 메모)
