---
layout: page
title: "Emacs JP で管理しているパッケージ"
description: "Emacs JP で管理しているパッケージ"
redirect_to: tips/emacs-jp-maintenance
---
{% include JB/setup %}

{{ site.title }} では、Emacs のパッケージをいくつか管理しています。
{{ site.title }} 独自のプロジェクトもありますが、特にメンテナンスされていないパッケージを集約しメンテナンスしています。

多くユーザーに利用されている定番といえるパッケージでも、メンテナンスがされていないために正しく動作しないものが増えてきています。
fork されて独自に修正されていることもありますが、修正が不完全なためにさらなるfork版が乱立してしまったりしています。

こういった混乱を防ぐためにも、ユーザー共同のリポジトリという点を生かして、これらのパッケージを集約しメンテナンス、アーカイブをしています。

## {{ site.title }} でメンテナンスしているパッケージ

* [elscreen](https://github.com/emacs-jp/elscreen)<br>
  Emacs にタブを追加します。 - [オリジナル](http://www.morishima.net/~naoto/elscreen-en/?lang=en)
* [init-loader](https://github.com/emacs-jp/init-loader)<br>
  Emacs の設定ファイルをカテゴリごとに複数のファイルに分割するのを支援します。 - [オリジナル](http://coderepos.org/share/browser/lang/elisp/init-loader/init-loader.el)
* [migemo](https://github.com/emacs-jp/migemo)<br>
  Migemo はローマ字のまま日本語をインクリメンタル検索するためのツールです。
  かな漢字変換をすることなく日本語のインクリメンタル検索を快適に行うことができます。- [オリジナル](http://0xcc.net/migemo/)
* [replace-colorthemes](https://github.com/emacs-jp/replace-colorthemes)<br>
  color-themeのテーマを Emacs24 の themeフレームワークに対応させています。

## {{ site.title }}で管理して欲しいパッケージの登録方法

[Issues](https://github.com/emacs-jp/issues/issues) に登録してください。

<!--
This file has been left for redirection.
Please do not add any content.
Redirect to /tips/emacs-jp-maintenance.
This file will be deleted after 6 month (2020/03/01).

;; Local Variables:
;; buffer-read-only: t
;; End:
-->
