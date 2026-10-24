---
title: "홈랩용 올인원 네트워크 게이트웨이 — DDNS·리버스 프록시·WAF·Tailscale을 단일 Go 바이너리로"
date: 2026-10-24T01:04:24.341749+00:00
verdict: "백로그"
tags: ["self-hosted", "network-gateway", "devops"]
source: "https://github.com/wangwanjie/gately"
source_name: "GitHub Trending (topic:self-hosted)"
status: "대기"
---
- **근거:** Go로 작성된 올인원 네트워크 게이트웨이 — DDNS, SNI 라우팅, 리버스 프록시, WAF, Tailscale, frp, Cloudflare Tunnel 등을 단일 바이너리로 제공하는 홈랩/서버 인프라 도구
- **액션:** git clone https://github.com/wangwanjie/gately 후 Docker Compose로 로컬 실행해 DDNS + 리버스 프록시 기본 동작 확인
