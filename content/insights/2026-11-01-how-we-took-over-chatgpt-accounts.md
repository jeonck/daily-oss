---
title: "ChatGPT HTML 프리뷰 iframe 공격 체인 분석 — postMessage·innerHTML·YouTube oEmbed CSP 우회"
date: 2026-11-01T01:28:08.131476+00:00
verdict: "학습"
tags: ["web-security", "csp-bypass", "iframe-sandbox"]
source: "https://simonwillison.net/2026/Oct/31/how-we-took-over-chatgpt-accounts/"
source_name: "Simon Willison"
status: "대기"
---
- **근거:** ChatGPT HTML 프리뷰 iframe의 postMessage→innerHTML→CSP우회 공격 체인을 다룬 보안 연구 기사 — 특정 오픈소스 저장소가 아니라 취약점 분석 글
- **액션:** postMessage 수신 시 innerHTML 대신 textContent/createElement 사용, iframe sandbox 속성 및 CSP script-src 허용 도메인 최소화 원칙을 내 프로젝트에 적용 여부 점검
