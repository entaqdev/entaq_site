+++
date = '{{ .Date }}'
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
linkTitle = '' # title短いバージョン
description = '{{ replace site.Params.description | description }}'
summary = '{{ description }}'
slug = '{{ replace .File.ContentBaseName | slug }}'
keywords = []
draft = true # --buildDrafts をつけるとレンダリングされる
weight = 100 # 1以上の正の整数（大きいほど下に表示される）
isCJKLanguage = true # 2バイト文字を考慮する
+++
