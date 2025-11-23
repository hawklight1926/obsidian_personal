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
Nadim Kobeissi氏は、Intel Comet Lake-H CPUとES8336オーディオコーデックを搭載したLenovo製ノートPCで、Linuxにおけるサウンド機能の有効化に6ヶ月間奮闘しました。
ES8336コーデックのLinuxサポートが不足しており、当初は音声出力もマイク入力も機能しませんでした。
彼はACPIダンプ解析やカスタムトポロジーファイルの作成を行い、sof-essx8336ドライバー内のマイク関連のバグを発見しました。
最終的に、このバグを修正するパッチをLinuxカーネルに提出し、それがマージされたことで、すべてのサウンド機能が動作するようになりました。
