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
Lenovo ThinkPad X1 Extreme Gen 5 (16IAX10H)において、Realtek ALC287コーデックとIntel ADL-Pチップセットの組み合わせに対するLinuxカーネルのサポート不足が原因で、スピーカーが機能しない問題が発生しました。

筆者は様々なカーネルバージョンやSOFファームウェア、コミュニティ開発のパッチを試行錯誤し、特にSOFプロジェクトへの貢献に注目しました。

最終的に、特定のSOFファームウェアコミットとカーネルパラメータの調整により、Ubuntu 24.04 (Linux 6.8) 環境でスピーカーを正常に動作させることに成功しました。

この解決策は将来のLinuxカーネル（6.9以降）に統合される見込みで、同様の問題を抱えるユーザーへの具体的な指針と、オープンソースコミュニティによる連携の重要性を示しています。
