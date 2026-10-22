---
title: "브라우저에서 Web Crypto로 파일 잠금: PBKDF2·HKDF·AES-GCM 청크 암호화 구현 사례"
date: 2026-10-22T00:54:06.449048+00:00
verdict: "학습"
tags: ["web-crypto", "frontend-security", "aes-gcm"]
source: "https://dev.to/kangchanghwan/locking-files-in-the-browser-with-web-crypto-pbkdf2-hkdf-and-1-mib-aes-gcm-records-4d50"
source_name: "DEV Community - showdev"
status: "대기"
---
- **근거:** 브라우저 Web Crypto API(PBKDF2→HKDF→AES-GCM 청크 암호화+서비스워커 스트리밍 복호화) 구현 패턴을 다룬 프론트엔드 보안 기술 글
- **액션:** Web Crypto API 청크 암호화 패턴(PBKDF2+HKDF 키 유도, 1 MiB AES-GCM records, 서비스워커 스트림 복호화) 코드 읽고 메모
