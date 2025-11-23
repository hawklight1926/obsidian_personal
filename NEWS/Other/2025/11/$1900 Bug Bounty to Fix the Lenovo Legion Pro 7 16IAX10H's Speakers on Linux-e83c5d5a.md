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
Nadim Kobeissi氏は、ASRock 16iax10hマザーボードを搭載したLinux PCで、Realtek ALC4080/ALC897内蔵サウンドが機能しない問題に直面しました。`lspci`では認識されるもののオーディオデバイスとして表示されず、様々なカーネルバージョンやドライバ設定を試しても音声が出ない状況が続きました。

筆者はBIOS設定やカーネルモジュール、ファームウェアの確認など多岐にわたるトラブルシューティングを実施。最終的に、問題はIntel Soundwireコーデックに関連するLinuxカーネルのバグである可能性が高いと推測しています。

記事執筆時点では根本的な解決策は見つかっておらず、ASRockのサポートと連携して調査を進めている段階です。
