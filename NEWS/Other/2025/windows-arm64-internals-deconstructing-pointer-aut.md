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
本記事は、Windows ARM64におけるポインタ認証（PAC）の内部構造を詳細に解説しています。PACはARMv8.3-Aで導入されたセキュリティ機能で、ポインタに暗号化された署名を埋め込むことで、ROPやJOPといった制御フロー攻撃を防ぐことを目的としています。

記事では、PACIASやAUTIAなどのARM命令、複数の署名キー、LSBへの署名格納メカニズムといった技術的詳細を深掘りしています。Windows 11がユーザーモードとカーネルモードの両方でPACをどのように活用し、システム全体のセキュリティを強化しているかを分析しています。
