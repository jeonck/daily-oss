---
title: "Zsh 히스토리 데이터 손실 버그 추적기"
date: 2026-08-09T23:04:40.262999+00:00
verdict: "학습"
tags: ["cli", "zsh", "debugging"]
source: "https://michael.stapelberg.ch/posts/2026-08-09-zsh-history-truncation-bug/"
source_name: "Lobsters"
status: "대기"
---
- **근거:** Zsh 히스토리 데이터 손실 버그를 추적한 기술 디버깅 기사 — 개발자 도구(CLI/셸) 영역에 해당하나 특정 오픈소스 저장소가 아닌 분석 글
- **액션:** Zsh 사용 시 HISTFILE 손실 방지를 위해 setopt APPEND_HISTORY, INC_APPEND_HISTORY, SHARE_HISTORY 옵션 적용 여부 점검
