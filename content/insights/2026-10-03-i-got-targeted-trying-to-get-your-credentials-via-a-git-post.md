---
title: "git post-checkout 훅으로 자격증명을 노린 공격 실제 사례"
date: 2026-10-03T01:26:40.151772+00:00
verdict: "학습"
tags: ["git-security", "credential-theft", "developer-security"]
source: "https://frankwiles.com/posts/i-got-targeted/"
source_name: "Lobsters"
status: "대기"
---
- **근거:** git post-checkout 훅을 악용한 자격증명 탈취 공격 사례 — 개발자 보안 인식 관련 기사
- **액션:** 로컬 git 저장소의 .git/hooks/ 디렉터리를 점검하고, 신뢰할 수 없는 저장소 클론 시 훅 자동 실행 위험을 인지하기
