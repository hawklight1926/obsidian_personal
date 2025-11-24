---
title: "Native Secure Enclave backed SSH keys on macOS"
url: "https://gist.github.com/arianvp/5f59f1783e3eaf1a2d4cd8e952bb4acf"
date: "2025-11-23"
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
macOS Tahoeでは、Secure Enclaveに裏打ちされたSSHキーがネイティブでサポートされるようになりました。
これにより、`/usr/lib/ssh-keychain.dylib` の `SecurityKeyProvider` を介して、Touch IDなどの生体認証を必要とするSSHキーを生成・利用できます。
生成したキーは `ssh-agent` に直接追加でき、`SSH_SK_PROVIDER` 環境変数を設定することで、シームレスなSSH認証が可能です。
この機能は、サードパーティ製ツールの使用を不要にし、より安全で便利な認証を実現します。エクスポート可能なキーの作成も可能です。
