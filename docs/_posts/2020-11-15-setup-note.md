---
layout: post
title: 個人的なメモをMarkdownで記録できるようにした
date: 2020-11-15 02:25
category: note
author: kuu
tags: []
summary: 
---

個人的なメモをMarkdown で記録できるようにした。

# 困っていた点
- メモをするのにGoogle Docs や Microsoft word に依存していた。
- そもそもメモしたものを記録する環境を整えてなかった

# 解決策
- Github へ Markdown 形式で公開するようにした
- Github へ Push すると Jekyll によってブログ形式へ整えるようにした
- GitHub or jekyll が死んでも Markdown 形式のファイルがまとまったフォルダは生き残る


# 工夫点
- Visual Studio の Markdown での記述サポートする Extension が良さそう
  - https://github.com/yzhang-gh/vscode-markdown
- Google Drive に一応バックアップを取っている
  - なんだかんだクラウドストレージには依存してしまいがち
- Google Domains で sub domain を割り当てた
