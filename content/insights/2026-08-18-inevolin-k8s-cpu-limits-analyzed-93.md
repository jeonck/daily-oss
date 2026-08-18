---
title: "Kubernetes CPU Limits가 앱을 느리게 만드는 이유 — 스로틀링 실증 분석"
date: 2026-08-18T23:00:46.878002+00:00
verdict: "백로그"
tags: ["kubernetes", "performance", "devops"]
source: "https://github.com/inevolin/k8s-cpu-limits-analyzed"
source_name: "GitHub Trending (topic:devops)"
status: "대기"
---
- **근거:** Kubernetes CPU throttling 분석 — DevOps/인프라 관심 분야에 직접 해당하는 K8s 운영 인사이트
- **액션:** git clone https://github.com/inevolin/k8s-cpu-limits-analyzed 후 docs/와 results/ 읽고, k8s/ 매니페스트와 scripts/로 로컬 클러스터에서 CPU throttling 재현 실험해보기
