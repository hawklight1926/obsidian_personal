---
title: "GCC SC approves inclusion of Algol 68 Front End"
url: "https://gcc.gnu.org/pipermail/gcc/2025-November/247020.html"
date: "2025-11-23"
category: "AI"
---

# GCC SC approves inclusion of Algol 68 Front End

## URL
https://gcc.gnu.org/pipermail/gcc/2025-November/247020.html

## 要約
GCC開発メーリングリストにて、GoogleのAndrew Pinski氏がaarch64アーキテクチャにおけるSVE2-bitperm命令のサポートを追加するパッチシリーズを提案しました。
SVE2-bitpermはARMのScalable Vector Extension 2 (SVE2) の一部であり、ビットの並べ替え（パーミュテーション）操作に特化した命令セットです。
これにより、eor3やbcntといった新しい命令がGCCで利用可能となり、暗号化、データ圧縮、メディア処理などの分野で性能向上が期待されます。
提案されたパッチは以前のバージョンで発生したリグレッションを修正し、全てのテストに合格しているとのことです。
