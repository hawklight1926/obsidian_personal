---
title: "GCC SC approves inclusion of Algol 68 Front End"
url: "https://gcc.gnu.org/pipermail/gcc/2025-November/247020.html"
date: "2025-11-23"
category: "AI"
---

# GCC SC approves inclusion of Algol 68 Front End

## URL
https://gcc.gnu.org/pipermail/gcc/2025-November/247020.html

## 要約
GCCのRichard Biener氏が、LTO（リンク時最適化）の並列コンパイルをデフォルトで有効にするパッチを提案しました。
これにより、単一の呼び出しで複数のコンパイル単位がある場合、デフォルトでCPUコア数に応じた並列処理が行われます。
`lto-wrapper`が長年この方式で成功しており、一般的なビルドシステム（makeなど）の挙動とも一致するため、より広範囲に適用することが目的です。
この機能は`-flto-partition=none`または`=1`で無効化でき、現在はフィードバックを求めるRFC（Request For Comments）の段階です。
