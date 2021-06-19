---
layout: post
title: StackEdit を Google Dride で利用することができない
date: 2020-11-15 05:10
category: 
author: kuu
tags: []
summary: 
parent: misc
---

Google Drive の拡張機能の「Stack Edit」を利用することができなかった。

# 現状
- 拡張機能のインストール時にGoogle アカウントでのログインを求められる。
- ログイン時にエラーが発生したとでる

# 原因を考えてみる

https://developers.google.com/apps-script/guides/client-verification

Google App Script で OAuth する時に審査があるのだが、それをしてない雰囲気を感じた。
(メンテされてなさそう...)