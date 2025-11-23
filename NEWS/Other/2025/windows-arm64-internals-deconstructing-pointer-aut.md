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
この記事は、Windows ARM64におけるポインター認証（PAC）の内部構造を深く掘り下げた解説です。PACはARMv8.3で導入されたセキュリティ機構で、ポインターの高位ビットに認証コードを埋め込み、ROP/JOPなどの制御フローハイジャック攻撃を防止します。

NTDLLなどのユーザーモードからカーネルモードまで幅広く利用され、特にWindows 11ではその適用範囲が拡大しています。これにより、システム全体のセキュリティを強化する重要な技術として機能しています。
