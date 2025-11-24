---
title: "Native Secure Enclave backed SSH keys on macOS"
url: "https://gist.github.com/arianvp/5f59f1783e3eaf1a2d4cd8e952bb4acf"
date: "2025-11-23"
updated: ""
categories: []
authors: ""
description: "Native Secure Enclave backed ssh keys on MacOS

It turns out that MacOS Tahoe can generate and use secure-enclave backed SSH keys! This replaces projects like https://github.com/maxgoedjen/secretive

There is a shared library /usr/lib/ssh-keychain.dylib that traditionally has been used to add smartcard support
to ssh by implementing PKCS11Provider interface. However since recently it also implements SecurityKeyProivder
which supports loading keys directly from the secure enclave! SecurityKeyProv..."
image: ""
read: false
ignored: false
pinned: false
---

## 要約
(要約生成に失敗しました)
