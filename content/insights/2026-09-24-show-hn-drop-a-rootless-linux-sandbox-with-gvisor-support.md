---
title: "Drop — gVisor 지원 루트리스 리눅스 샌드박스 (로컬 서드파티 실행 격리)"
date: 2026-09-24T00:52:59.772018+00:00
verdict: "학습"
tags: ["linux-sandbox", "supply-chain-security", "developer-tools"]
source: "https://droprun.sh/"
source_name: "HN (show hn)"
status: "대기"
---
- **근거:** 로컬 개발 환경에서 서드파티 프로그램을 Linux 네임스페이스 + gVisor로 격리 실행하는 개발자 보안 도구 — DevOps/개발자 도구 분야에 해당
- **액션:** droprun.sh 사이트에서 GitHub 저장소 링크 확인 후 README 검토, 로컬에서 의심스러운 npm/pip 패키지 실행 시 Drop으로 격리 테스트
