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
ARMv8.3で導入されたポインター認証（PA）は、ポインターに暗号署名を付与し、メモリ破損攻撃を防ぐためのセキュリティ機能です。

Windows ARM64はPAを実装しており、カーネルレベルのポインターやAPC（非同期プロシージャコール）などで積極的に利用し、システムの中核的な整合性を保護しています。

しかし、現在のところ、ユーザーモードアプリケーションの一般的なポインター保護には広く適用されていません。

将来的にはユーザーモードでのさらなる活用が期待される、潜在的に強力なセキュリティ機能です。
