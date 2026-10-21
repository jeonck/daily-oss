---
title: "eMudhra 중간 CA 개인키 유출 — Python 도구·OS 인증서 즉시 업데이트 필요"
date: 2026-10-21T00:56:51.911644+00:00
verdict: "즉시조치"
tags: ["security", "python", "pki"]
source: "https://simonwillison.net/2026/Oct/20/emudhra-certificates/"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** Python/DevOps/CI 환경 전반에 영향을 주는 CA 인증서 키 유출 — certifi·pip·uv 업데이트 필요
- **액션:** pip install --upgrade certifi pip (목표: certifi≥2026.10.19, pip≥26.2.2), uv self update (목표: ≥0.13.4), Linux 서버·CI 이미지는 ca-certificates 패키지 업데이트 후 컨테이너 리빌드
