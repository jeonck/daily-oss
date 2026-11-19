---
title: "Replit 공개 셀프호스티드 관측성 플랫폼 — OTel 수집·PostgreSQL/ClickHouse 저장·대시보드 올인원"
date: 2026-11-19T03:51:02.220308+00:00
verdict: "즉시조치"
tags: ["observability", "opentelemetry", "self-hosted"]
source: "https://github.com/replit/datacat"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** DevOps/인프라 모니터링·관측성 분야 — OpenTelemetry 기반 셀프호스티드 all-in-one 관측성 플랫폼(메트릭·로그·트레이스·대시보드·알림)으로 PostgreSQL/ClickHouse 백엔드 지원
- **액션:** git clone https://github.com/replit/datacat && docker-compose up -d 로 로컬 기동 후 OTel collector 연결해 메트릭/트레이스 수집 PoC 확인
