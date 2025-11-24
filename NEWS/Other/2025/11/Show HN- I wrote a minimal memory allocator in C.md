---
title: "Show HN: I wrote a minimal memory allocator in C"
url: "https://github.com/t9nzin/memory"
date: "2025-11-23"
updated: ""
category: "Other"
tags: []
authors: ""
description: "<a href=\"https://news.ycombinator.com/item?id=46027962\">Comments</a>"
image: ""
read: false
ignored: false
pinned: false
---

## 要約
このプロジェクトは、C言語で`malloc`、`calloc`、`realloc`、`free`をカスタム実装したメモリPアロケータです。

小規模な割り当てには`sbrk`、大規模な割り当てには`mmap`を使用し、ブロックの分割や結合でフラグメンテーション削減と効率化を図っています。

ただし、スレッドセーフではないため、並行処理での利用は未定義動作を引き起こします。

静的ライブラリとして利用可能で、実装の詳細を解説したブログ記事も公開されています。
