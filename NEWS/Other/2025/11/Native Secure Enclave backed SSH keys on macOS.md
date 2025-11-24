---
title: "Native Secure Enclave backed SSH keys on macOS"
url: "https://gist.github.com/arianvp/5f59f1783e3eaf1a2d4cd8e952bb4acf"
date: "2025-11-23"
updated: ""
category: "Other"
tags: []
authors: ""
description: "Comments"
image: ""
read: false
ignored: false
pinned: false
---

## 要約
macOS Sonomaでは、Secure EnclaveをネイティブでSSHキーのバックエンドとして利用できるようになった。これは、`/usr/lib/ssh-keychain.dylib`が`SecurityKeyProvider`インターフェースを実装したことで実現し、Touch IDなどのバイオメトリクス認証でSSHキーを安全に管理できる。

`ssh-keygen -t sk-ecdsa`コマンドでキーを生成し、`ssh-add`で`ssh-agent`に登録するか、公開鍵をサーバに設定して使用する。環境変数`SSH_SK_PROVIDER`を設定すれば、デフォルトでSecure Enclaveをプロバイダーとして利用可能。

これにより、`secretive`のようなサードパーティツールなしで、高セキュリティなSSH認証環境を構築できる。
