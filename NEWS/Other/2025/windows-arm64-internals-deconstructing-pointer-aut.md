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
Windows ARM64版に実装されているセキュリティ機能「ポインタ認証（PA）」は、メモリ破損攻撃、特にROPのようなコントロールフローハイジャック攻撃を防ぐためのものです。この機能は、ポインタの未使用ビットに暗号学的署名（PAC）を埋め込み、実行時にそのポインタが改ざんされていないかを検証します。

WindowsカーネルではPAが広く採用されており、ユーザーモードでもEdgeブラウザの一部モジュールなどで利用が始まっています。これによりOSの堅牢性が向上しますが、完璧な防御策ではなく、他のセキュリティ機能との連携が重要であると指摘されています。
