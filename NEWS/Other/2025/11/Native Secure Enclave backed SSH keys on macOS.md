---
title: "Native Secure Enclave backed SSH keys on macOS"
url: "https://gist.github.com/arianvp/5f59f1783e3eaf1a2d4cd8e952bb4acf"
date: "2025-11-23"
updated: ""
category: "Other"
tags: []
authors: ""
description: "<a href=\"https://news.ycombinator.com/item?id=46025721\">Comments</a>"
image: ""
read: false
ignored: false
pinned: false
---

## 要約
最新のmacOSでは、Secure Enclaveを活用してSSHキーを生成・保存し、Touch IDなどの生体認証でSSHログインができるようになりました。これは`/usr/lib/ssh-keychain.dylib`がFIDO2デバイスと同様の`SecurityKeyProvider`として機能することで実現され、`secretive`のような従来のサードパーティ製ツールが不要になります。

`ssh-keygen -t sk-ecdsa -O resident`コマンドでキーを作成し、`ssh-add -K`で`ssh-agent`に直接登録可能。`SSH_SK_PROVIDER`環境変数を設定することで、Secure Enclaveに格納されたキーをデフォルトで使用できます。これにより、安全かつ非常に便利なSSH認証フローが実現します。
