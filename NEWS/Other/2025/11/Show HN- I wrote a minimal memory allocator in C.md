---
title: "Show HN: I wrote a minimal memory allocator in C"
url: "https://github.com/t9nzin/memory"
date: "2025-11-23"
updated: ""
category: "Other"
tags: []
authors: ""
description: "Comments"
image: ""
read: false
ignored: false
pinned: false
---

## 要約
このプロジェクトは、C言語で`malloc`、`calloc`、`realloc`、`free`などの標準関数を独自に実装したカスタムメモリSアロケータです。

小規模な割り当てには`sbrk`、大規模な割り当てには`mmap`を利用し、断片化を減らすためのブロック分割や隣接する空きブロックのマージといった最適化が施されています。

ただし、このアロケータはスレッドセーフではないため、並行呼び出しを行うと未定義の動作を引き起こす点に注意が必要です。
