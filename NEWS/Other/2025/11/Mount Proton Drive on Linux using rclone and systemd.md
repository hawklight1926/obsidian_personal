---
title: "Mount Proton Drive on Linux using rclone and systemd"
url: "https://github.com/dadtronics/protondrive-linux"
date: "2025-11-23"
updated: ""
category: "Other"
tags: []
authors: ""
description: "<a href=\"https://news.ycombinator.com/item?id=46024584\">Comments</a>"
image: ""
read: false
ignored: false
pinned: false
---

## 要約
本記事は、`rclone`と`systemd`を利用してProton DriveをLinuxに自動マウントするための詳細なガイドです。
`fuse3`と`rclone`をインストールし、Proton Driveのリモート設定後、提供されるセットアップスクリプトを実行するだけで簡単に設定が完了します。
これにより、Proton Driveはシステム起動時に自動マウントされ、ローカルの`/ProtonDrive`ディレクトリからファイルにアクセス可能となります。
Arch Linuxでテスト済みですが、多くのLinuxディストリビューションで動作し、検証・アンインストール・トラブルシューティング情報も提供されています。
