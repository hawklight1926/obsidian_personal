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
Intel NUC 13 Pro (Arena Canyon)でLinuxを使用する際、音が出ないという問題が報告されています。これは、Thunderbolt/USB-Cコントローラーがオーディオドライバー`sof-hda-dsp`の初期化を妨げていることが原因です。

一時的な解決策として、BIOSでThunderbolt/USB-Cコントローラーを無効にするとHDMIやアナログオーディオは機能するようになります。しかし、この方法ではThunderbolt機能自体が利用できなくなります。

この問題は多くのLinuxディストリビューションで確認されており、今後のソフトウェアまたはファームウェアによる修正が期待されています。
