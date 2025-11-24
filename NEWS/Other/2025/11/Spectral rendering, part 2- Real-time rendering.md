---
title: "Spectral rendering, part 2: Real-time rendering"
url: "https://momentsingraphics.de/SpectralRendering2Rendering.html"
date: "2025-11-14"
updated: ""
category: "Other"
tags: []
authors: ""
description: "<a href=\"https://news.ycombinator.com/item?id=45922514\">Comments</a>"
image: ""
read: false
ignored: false
pinned: false
---

## 要約
この記事は、スペクトルレンダリングにおける光と物質の相互作用を表す積分の、リアルタイムでの効率的な評価方法を探求しています。従来の高次元ベクトルによる近似法が不正確で高コストである問題を指摘し、モンテカルロ積分と重点サンプリングの利用を提案。

重点サンプリングでは、既知の照明スペクトルとCIE XYZ色関数（またはRGB色関数）の1-ノルムに基づいて確率密度関数を定義します。反射スペクトルは事前に不明で比較的滑らかなため、重点サンプリングでは考慮されません。

実装には、逆CDFサンプリングを用いて適切な波長を抽出し、それらの波長での貢献度を計算する方法が示されています。これにより、正確な色再現と計算コストの削減を両立させることを目指しています。
