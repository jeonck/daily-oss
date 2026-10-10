---
title: "SSH·Docker·DB·AI 통합 터미널 워크벤치 NexTerm"
date: 2026-10-10T01:54:54.375559+00:00
verdict: "백로그"
tags: ["developer-tools", "devops", "terminal"]
source: "https://github.com/Hello-CTF/NexTerm"
source_name: "GitHub Trending (topic:devops)"
status: "대기"
---
- **근거:** SSH·SFTP·Docker·DB·AI를 통합한 터미널 워크벤치로 개발자 도구 및 DevOps 인프라 관리 분야에 해당
- **액션:** git clone https://github.com/Hello-CTF/NexTerm 후 Wails 기반 데스크톱 앱 빌드(go install github.com/wailsapp/wails/v2/cmd/wails@latest → wails dev) 해보고 SSH/Docker 연결 기능 동작 확인
