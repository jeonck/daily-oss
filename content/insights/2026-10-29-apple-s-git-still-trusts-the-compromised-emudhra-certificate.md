---
title: "Apple의 git이 손상된 eMudhra 인증서를 여전히 신뢰 중"
date: 2026-10-29T01:56:59.991401+00:00
verdict: "학습"
tags: ["security", "git", "certificates"]
source: "https://emudhra.we-have-a-problem.com/apple.html"
source_name: "Lobsters"
status: "대기"
---
- **근거:** macOS 환경 git의 인증서 신뢰 체계 관련 보안 이슈 — 개발자 도구/보안 관심 분야에 해당하나 클론·도입 대상 OSS 프로젝트는 없음
- **액션:** macOS 사용 시 Keychain 접근 → 시스템 루트 인증서 목록에서 eMudhra 관련 CA 신뢰 상태 확인 (security find-certificate -a -p /System/Library/Keychains/SystemRootCertificates.keychain | openssl x509 -text -noout 2>/dev/null | grep -i emudhra)
