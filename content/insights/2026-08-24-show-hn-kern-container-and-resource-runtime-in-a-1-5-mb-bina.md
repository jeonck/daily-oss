---
title: "Kern: 데몬 없는 1.5MB Rust 컨테이너·리소스 런타임 (3.5ms 기동)"
date: 2026-08-24T23:01:11.663890+00:00
verdict: "백로그"
tags: ["container-runtime", "devops", "rust-cli"]
source: "https://github.com/getkern/kern"
source_name: "HN (show hn)"
status: "대기"
---
- **근거:** 데몬 없이 OCI 컨테이너를 실행하는 경량 Rust 바이너리로, DevOps/인프라·AI 에이전트 격리 실행 도구 영역에 해당
- **액션:** git clone https://github.com/getkern/kern 후 단순 작업(CPU/RAM 제한 컨테이너 실행) 하나를 Docker와 기동 시간·리소스 사용량 비교해보기
