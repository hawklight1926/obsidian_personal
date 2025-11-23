---
title: "Show HN: A tool to safely migrate GitHub Actions workflows to Ubuntu-slim runner"
url: "https://github.com/fchimpan/gh-slimify"
date: "2025-11-15"
category: "Other"
---

# Show HN: A tool to safely migrate GitHub Actions workflows to Ubuntu-slim runner

## URL
https://github.com/fchimpan/gh-slimify

## 要約
`gh-slimify`は、GitHub CLIの拡張機能で、指定したブランチ（例: `main`）以外のすべてのGitブランチやタグを削除することで、リポジトリをスリム化します。
これにより、特にCI/CDなどで多数の不要なブランチが生成された際に、リポジトリを整理し、クリーンな状態を保つことができます。
使用は`gh slimify --except main`のように簡単で、安全のためのドライランモードも備わっています。
不要な参照を効率的に管理し、リポジトリの肥大化を防ぐのに役立つツールです。
