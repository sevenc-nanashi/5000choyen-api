﻿# 5000choyen-api
5000兆円欲しい！をnode-canvasを使用しサーバーサイドで生成できるようにしたものです。

# how to use

https:\/\/gosenchoyenapi.herokuapp.com/image?top=上部文字列&bottom=下部文字列

↓

![](https://gosenchoyenapi.herokuapp.com/image?top=上部文字列&bottom=下部文字列)

# spec
画像形式: PNG (アルファチャンネルあり、背景透明)

基本解像度: 1920x1080

# caution

基本解像度は1920x1080ですが、文字列の長さによっては横幅が増える可能性があります。

Herokuでホストしていますが、過剰なアクセスはお控えください。

# thanks
このプログラムは、yurafuca様が作られたものをベースにNode.js向けに改良を加えつつ、サーバーサイドに移植したものです。
原作リポジトリは[こちら](https://github.com/yurafuca/5000choyen)

# fonts
このジェネレーターは以下のフォントを使用しています。

Noto Sans JP Black

Noto Serif JP Black

これらのフォントはオープンフォントライセンスに基づきGoogle Fontsよりダウンロード可能です。
