---
title: "PHP session.upload_progress 인증 없는 RCE 체인 PoC + Suricata/Sigma/ModSecurity 탐지 룰 모음"
date: 2026-10-23T00:56:19.508991+00:00
verdict: "백로그"
tags: ["security", "cve", "detection-rules"]
source: "https://github.com/ikow/php2shell-poc"
source_name: "GitHub Trending (stars:>200)"
status: "대기"
---
- **근거:** PHP pre-auth RCE CVE PoC이며 Suricata·Sigma·ModSecurity 탐지 룰까지 포함 — DevOps/인프라 보안 모니터링 영역에 직접 해당
- **액션:** git clone https://github.com/ikow/php2shell-poc 후 detection/ 폴더의 Sigma·Suricata 룰을 검토하고 ModSecurity 룰 적용 가능성 평가
