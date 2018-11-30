---
title: "Hugo + Github Pages でブログを作る"
date: 2018-12-01T03:13:11+09:00
draft: false
---

このブログのような静的サイトジェネレータとホスティングサービスの組み合わせでブログが作成されていると思う。

今回は同僚のLT（ Lightning Talks ）を聞いて興味を持ち、今この真夜中に筆を取っている。

実験的なもので続くかはわからないが、何でもやってみるの精神で構築してみる。

例に倣って、 `Hugo` + `Github Pages` で作成する。

もしやる気が出れば [Netlify](https://www.netlify.com/) に手を出すかもしれない。


```bash
$ brew install hugo
$ hugo new site blog
$ cd blog
$ git init
$ git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/gohugo-theme-ananke
$ hugo new posts/example.md
```
