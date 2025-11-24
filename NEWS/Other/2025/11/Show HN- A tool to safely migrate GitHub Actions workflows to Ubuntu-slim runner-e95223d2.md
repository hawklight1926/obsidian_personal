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
「gh-slimify」は、GitHub CLIの出力が冗長で読みにくいという課題を解決するために作られた拡張機能です。

このツールは、`gh pr list`や`gh issue list`などのコマンド実行時に、JSON形式の不要なノイズや詳細情報を自動で取り除きます。これにより、プルリクエストのタイトル、ステータス、作成者、日付といった重要な情報のみを抽出し、人間が読みやすい簡潔な形式で表示します。

ユーザーはYAMLやGoテンプレートを用いて出力形式を柔軟にカスタマイズでき、GitHub CLIの利便性を損なうことなく、より効率的な情報把握とワークフローの改善が可能になります。インストールも簡単で、GitHub CLIのサブコマンドとして機能します。
