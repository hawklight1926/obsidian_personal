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
Windows ARM64のポインター認証（PA）は、メモリ破損攻撃に対する強力な防御機能です。本記事では、Qualcomm Snapdragon X EliteプロセッサにおけるPAの内部構造と、そのバイパス手法を詳しく解説しています。

特に、Qualcommチップに備わるデバッグ機能「QAx」が悪用されると、特権レベルでPA検証が無効化され、セキュリティが著しく低下する脆弱性を発見しました。これにより、ROP/JOP攻撃などに対する重要な防御が迂回されるリスクがあり、既にMicrosoftに報告されています。
