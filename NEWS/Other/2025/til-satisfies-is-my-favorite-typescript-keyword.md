---
title: "TIL: `satisfies` is my favorite TypeScript keyword"
url: "https://sjer.red/blog/2024-12-21/"
date: "2025-11-18"
category: "Other"
---

# TIL: `satisfies` is my favorite TypeScript keyword

## URL
https://sjer.red/blog/2024-12-21/

## 要約
本記事では、2000年代初頭のmacOS Aqua UIにおける独特なプログレスバーをSwiftUIで再現する試みについて解説しています。
SwiftUIでネイティブなぼかし効果を直接適用する難しさがあるため、背景のぼかし表現に工夫が必要とされました。
そこで、`ViewModifier`、`mask`、`blur`などのSwiftUIの機能を組み合わせることで、特定の形状の内部のみをぼかす「フロストグラス」のような視覚効果を実現。
Aqua UIの特徴である半透明でぼかされた質感とアニメーションを忠実に再現した、その詳細なコードと結果が示されています。
