---
title: "Show HN: I wrote a minimal memory allocator in C"
url: "https://github.com/t9nzin/memory"
date: "2025-11-23"
updated: ""
category: "Tech"
tags: []
authors: ""
image: ""
memo: ""
read: false
ignored: false
pinned: false
---

## 要約
このプロジェクトは、`sbrk`を小規模、`mmap`を大規模な割り当てに利用してゼロから記述されたメモリ・アロケーターです。
断片化を削減するためのブロック分割や、隣接する空きブロックを結合する合体といった最適化が組み込まれています。
ただし、このアロケーターはスレッドセーフではなく、並行呼び出しは未定義の動作を引き起こします。
開発プロセスを詳しく解説したブログ記事も提供されており、静的ライブラリとしてビルドしてC言語プロジェクトで使用可能です。
