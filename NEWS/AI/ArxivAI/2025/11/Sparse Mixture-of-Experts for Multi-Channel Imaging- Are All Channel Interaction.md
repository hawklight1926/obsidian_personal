---
title: "Sparse Mixture-of-Experts for Multi-Channel Imaging: Are All Channel Interactions Required?"
url: "https://arxiv.org/abs/2511.17400"
date: "2025-11-24"
updated: ""
category: "AI"
tags: []
authors: "Sukwon Yun, Heming Yao, Burkhard Hoeckendorf, David Richmond, Aviv Regev, Russell Littman"
image: ""
memo: ""
read: false
ignored: false
pinned: false
---

## 要約
本論文は、多チャネル画像処理におけるCNNの高い計算コストとメモリ消費の問題に対し、Sparse Mixture-of-Experts (Sparse-MoE) フレームワークを提案します。これは、すべてのチャネル相互作用が等しく重要ではないという洞察に基づき、学習可能なゲーティングメカニズムを用いて特定のチャネル相互作用にのみ専門家ネットワークを選択的に活性化し、冗長な計算を削減する手法です。

ハイパースペクトル画像超解像や医用画像セグメンテーションなど多様な多チャネル画像タスクにおいて、既存手法より大幅な効率向上と、同等またはそれ以上の性能を実証しました。これにより、より効率的でスケーラブルなCNNアーキテクチャへの道を開きます。
