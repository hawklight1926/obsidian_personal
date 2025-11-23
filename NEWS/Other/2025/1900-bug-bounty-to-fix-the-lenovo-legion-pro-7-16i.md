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
このリポジトリは、Intel Core Ultra 16iax10hを搭載したFramework 16ノートPCで、Linux上で音が出ない問題の解決過程を記録したものです。

この問題は、新しいIntel CPUにおいてHDAコントローラーのACPIエントリが欠落していることが原因でした。

Mario Limonciello氏が作成したカーネルパッチが、特定のハードウェア用の「quirk」を追加することでこれを解決。

著者はこの保留中のパッチを手動で適用して音声を復旧させ、現在は公式のLinuxカーネルへの統合を待っています。
