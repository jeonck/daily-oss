---
title: "가상화 없이 Linux에서 Microsoft Office 실행하는 Nix Flake PoC"
date: 2026-09-19T00:38:09.586031+00:00
verdict: "백로그"
tags: ["linux", "wine", "nix-flakes"]
source: "https://github.com/Tombert/office365_flake"
source_name: "HN (show hn)"
status: "대기"
---
- **근거:** Linux 데스크톱 환경에서 Microsoft Office를 가상화 없이 실행하는 Nix Flake 구성 — 개발자 도구/시스템 관리 관심 분야에 해당
- **액션:** git clone https://github.com/Tombert/office365_flake 후 Nix Flakes 환경(NixOS + Wayland)에서 `nix run` 실행해 Office 365 동작 확인
