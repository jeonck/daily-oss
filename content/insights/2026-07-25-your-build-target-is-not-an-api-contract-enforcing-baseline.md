---
title: "Vite 빌드 타겟은 API 계약이 아니다 — TypeScript로 Baseline 호환성 강제하기"
date: 2026-07-25T23:42:09.993360+00:00
verdict: "학습"
tags: ["typescript", "vite", "frontend"]
source: "https://dev.to/ryuya/your-build-target-is-not-an-api-contract-enforcing-baseline-with-typescript-epn"
source_name: "DEV Community - showdev"
status: "완료"
---
- **근거:** TypeScript/Vite 빌드 타겟과 Baseline API 가용성 간의 간극을 설명하는 프론트엔드 개발 기술 아티클
- **액션:** typescript-baseline-lib 및 @baseline-types/dom-widely-available 패키지를 찾아보고, 사용 중인 Vite 프로젝트에 별도 tsconfig로 CI 체크 추가 방법 검토
