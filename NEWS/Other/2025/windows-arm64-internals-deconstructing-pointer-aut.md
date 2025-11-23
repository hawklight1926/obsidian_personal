---
title: "Windows ARM64 Internals: Deconstructing Pointer Authentication"
url: "https://www.preludesecurity.com/blog/windows-arm64-internals-deconstructing-pointer-authentication"
date: "2025-11-22"
category: "Other"
---

# Windows ARM64 Internals: Deconstructing Pointer Authentication

## URL
https://www.preludesecurity.com/blog/windows-arm64-internals-deconstructing-pointer-authentication

## 要約
この記事は、Windows ARM64におけるポインター認証（PA）というセキュリティ機能の内部実装を深く掘り下げています。
PAは、ポインターに暗号署名を付与し、使用時にその整合性を検証することで、ROP（Return-Oriented Programming）などのポインターベースの攻撃を防ぎます。
記事では、ARMのハードウェア機能を利用したOSレベルでの動作、PACキーの管理、PEB構造体への統合、そしてプロセスごとの有効化や設定方法が詳細に解説されています。
これにより、Windows 11 24H2以降で強化された、低レベルのメモリ保護メカニズムが明らかにされています。
