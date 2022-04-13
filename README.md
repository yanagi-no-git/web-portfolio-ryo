# web-portfolio-ryo

# web-portfolio-yumi

このプロジェクトは、ポートフォリオのソースコードです。

## コンテナ起動

起動するときは以下のコマンドを入力します。
プロジェクトルートでコマンドを実行する必要があります。

```sh
# Start
$ docker run -dit --rm --name portfolio1 -v "$PWD/public":/usr/local/apache2/htdocs/ -p 3000:80 httpd:2.4-alpine
```

## アクセス

コンテナ起動中は、以下の URL にアクセスできます。

<http://localhost:3000/>

## コンテナ終了

制作終了時は以下のコマンドでコンテナを終了します。

```sh
$ docker stop portfolio1
```

## indexで雛形作成

！と入力してenterすると雛形が作成できる

##　ショートカットキー

command+A　全て選択
command+S　上書き保存
：いろんな知識を学んで、それを使えるようになるのが気持ちいい

##　知識

検索「DOCTYPE html」 (opens new window)
検索「meta charset UTF-8」 (opens new window)
検索「X-UA-Compatible」 (opens new window)
検索「meta viewport」 (opens new window) 重要

## CSSでできること
・フォントを変える
　Googleフォントからインポートする
・ボタンのデザインを変える
　cssのデフォルトデザインがダサいらしい
文章の揃え方や間隔も変えられる

##　簡単なプログラマイング方法

・例えば、<div>を作りたければ、<から始めずに、dと打ってみる。すると候補を表示してくれるから簡単！！

## 用語を調べたいときはこのサイト！！！
https://developer.mozilla.org/ja/docs/Web/CSS/position
mdn　っていう会社？のサイト
サイト内で実際にコードを使ってみれるのでわかりやすい！！
