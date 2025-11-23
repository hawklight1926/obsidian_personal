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
この記事は、Windows on ARM64におけるポインタ認証（PA）の内部構造と、それがROP/JOPなどのメモリ破損攻撃からシステムを保護する仕組みを詳細に解説しています。ARMv8.3で導入されたPAは、ポインタの未使用ビットに暗号学的ハッシュ（PAC）を埋め込み、ポインタの改ざんを検知することで整合性を保証します。

Windows 11 ARM64では、特にカーネルモードで特定の関数ポインタ保護に利用され、ユーザーモードでもリターンアドレスや例外ハンドラの保護（ROPガード）として活用される可能性が指摘されています。記事は、実際のシステムでのPAC命令の使用状況や具体的な実装例を分析し、そのセキュリティメカニズムを深く掘り下げています。
