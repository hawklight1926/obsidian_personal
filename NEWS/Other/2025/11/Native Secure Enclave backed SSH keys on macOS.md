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
macOS Ventura (Tahoe) 以降では、デバイスのSecure Enclaveを活用したSSHキーの生成と利用が可能になりました。これにより、Touch IDなどの生体認証でSSHキーを保護し、従来のサードパーティ製ツールなしで安全な認証を実現できます。

OSが提供する`/usr/lib/ssh-keychain.dylib`がFIDO2デバイスと同様のSecurityKeyProviderインターフェースを実装することで、`ssh-keygen`コマンドで生体認証を要求するキーを生成し、`ssh`や`ssh-agent`で直接利用できます。`SSH_SK_PROVIDER`環境変数を設定すれば、デフォルトでSecure Enclaveキーを扱うことも可能です。

この機能により、SSHキーのセキュリティと利便性が向上します。
