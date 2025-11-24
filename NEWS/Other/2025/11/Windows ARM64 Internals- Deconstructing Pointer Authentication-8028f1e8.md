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
このブログ記事は、ARM64アーキテクチャに導入されたポインタ認証（PA）の内部動作に焦点を当てています。PAは、暗号化されたハッシュ（PAC）と秘密鍵を用いてポインタを署名・認証することで、ポインタの破損を防ぐセキュリティ機能です。

WindowsはユーザーモードでPAを積極的に活用しており、特に戻りアドレス保護（RAP）や例外処理において、ポインタの安全性を高めています。カーネルは`NtSetInformationThread`を通じてスレッドごとに異なる認証鍵を割り当て、その詳細な設定とPAがどのように機能するかが解説されています。
