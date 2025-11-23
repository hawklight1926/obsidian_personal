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
この記事は、Windows ARM64環境におけるポインター認証 (PA) の内部実装を詳細に解説しています。
ARMv9で導入されたPAは、ポインターの認証コード(PAC)によって整合性を確保し、ROP/JOPなどのメモリ破損攻撃の緩和に貢献するセキュリティ機能です。
Windowsでは、カーネル（ntoskrnl.exe）とユーザーモード（ntdll.dll）の両方でPAが活用されており、スタックやページテーブルの保護などに利用されていることが明らかにされました。
これはARMv9チップを搭載するWindowsデバイスのセキュリティを強化するものであり、今後のさらなる適用範囲拡大が期待されます。
