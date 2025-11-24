---
title: "Hyperoptic: IPv6 and Out-of-Order Packets"
url: "https://blog.zakkemble.net/hyperoptic-ipv6-and-out-of-order-packets/"
date: "2025-11-18"
updated: ""
category: "Tech"
tags: []
authors: ""
image: ""
memo: ""
read: false
ignored: false
pinned: false
---

## 要約
HyperopticのIPv6接続において、ルーター再起動後にISPルーターがルーター要請(RS)に応答せず、ルーター広告(RA)が遅れてIPv6接続が不安定になる問題が発生しました。これはWANインターフェースのMACアドレスを変更するか、デフォルトゲートウェイを手動で追加することで一時的に回避可能です。

さらに、WANインターフェースのMACアドレスが「4」または「6」で始まる場合、パケットが順序通りに届かない（Out-of-Order）問題が確認されました。これはルーターがMACアドレスの先頭ニブルを見てパケットタイプを誤認識することが原因です。

MACアドレスを「4」または「6」以外の値に変更することで、このOutOfOrderパケット問題は解消されました。
