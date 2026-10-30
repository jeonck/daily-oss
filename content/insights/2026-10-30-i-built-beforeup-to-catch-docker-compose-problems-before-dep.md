---
title: "BeforeUp - Docker Compose 배포 전 호스트 조건 사전 검증 도구"
date: 2026-10-30T02:08:48.190963+00:00
verdict: "백로그"
tags: ["docker-compose", "devops", "pre-deployment"]
source: "https://dev.to/breezedelegate/i-built-beforeup-to-catch-docker-compose-problems-before-deployment-51h2"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** Docker Compose 배포 전 포트 충돌·바인드 마운트 누락 등 호스트 사이드 조건을 사전 검증하는 DevOps/인프라 도구
- **액션:** GitHub에서 'BeforeUp beforeup docker-compose' 검색 후 저장소 클론, 기존 compose.yaml에 `beforeup check -f compose.yaml` 실행하여 경고/블로커 탐지 확인
