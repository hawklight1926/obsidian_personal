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
この記事は、Lenovo Thinkpad 16IAX10HでLinux上のサウンドが全く機能しないという、著者の「サガ」を詳述しています。

問題は、内蔵のIntel Meteor Lakeオーディオコントローラー（デバイス7a88）に対するLinuxカーネルのサポートが不足していたことにありました。

著者は多くのデバッグと試行錯誤の末、Intelエンジニアによるこの問題への特定のカーネルパッチを発見。

そのパッチをカスタムビルドしたLinux 6.6カーネルにバックポートすることで、ようやくサウンド出力が機能するようになりました。この修正は、Linux 6.8以降のカーネルに正式に含まれています。
