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
Lenovo ThinkPad P1 Gen 6 (16IAX10H) で、Linuxのサウンドが認識されない（ダミー出力となる）問題が長らく存在していました。これはRealtek ALC3306コーデック用の「オーディオDSPトポロジーデータ」がファームウェアから提供されないことに起因します。

筆者はWindowsドライバーをリバースエンジニアリングしてこのデータを特定し、当初はカーネルパッチで適用。最終的にこのデータと設定がLinuxカーネルv6.10-rc1にマージされることに成功しました。これにより、P1 Gen 6でのLinuxサウンドが箱から出してすぐに機能するようになり、複雑な互換性問題が解決されました。
