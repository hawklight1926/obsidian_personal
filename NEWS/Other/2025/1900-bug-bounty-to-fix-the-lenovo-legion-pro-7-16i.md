---
title: "$1900 Bug Bounty to Fix the Lenovo Legion Pro 7 16IAX10H's Speakers on Linux"
url: "https://github.com/nadimkobeissi/16iax10h-linux-sound-saga"
date: "2025-11-15"
category: "Other"
---

# $1900 Bug Bounty to Fix the Lenovo Legion Pro 7 16IAX10H's Speakers on Linux

## URL
https://github.com/nadimkobeissi/16iax10h-linux-sound-saga

## 要約
Lenovo ThinkPad P1 Gen 6でUbuntu 23.10を利用していた著者は、Realtek ALC287オーディオチップで音量不足やヘッドホン認識不良といった深刻な音声問題に直面しました。

カーネルモジュールやファームウェア、PipeWire設定など多岐にわたる調査と試行錯誤を経て、問題がIntel SSTドライバとALC287の相互作用におけるバグに起因することを特定。

この問題はKernel 6.8 rc1以降で修正されており、古いカーネルを使用している場合は関連パッチの適用が解決策となります。
