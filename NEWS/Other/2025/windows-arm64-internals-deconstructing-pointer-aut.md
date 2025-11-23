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
本記事は、ARM64の強力なハードウェアセキュリティ機能「ポインタ認証（PAC）」について、Windows上での内部実装を詳細に分析しています。
PACはメモリ破損攻撃対策として重要ですが、Windows on ARM64の現行実装は限定的であることが明らかになりました。
具体的には、保護対象がリターンアドレスと例外ハンドラのポインタに留まっており、他の多くの重要なポインタは保護されていません。
このため、PACの防御効果は期待値より低く、攻撃者による悪用の余地が残されていると指摘しています。
