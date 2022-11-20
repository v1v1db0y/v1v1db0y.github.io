hugoの使い方。

#新しく記事を書きたいと思ったら
> hugo new post/[書きたい記事のタイトル]/index.md
て入力してね。

#記事を書いたのに表示されない！
> index.md を開いて設定のところの
> [math: true]
> これをfoursにしてみてね。
> それでもだめら消してみて

#記事の設定画面たち！
## author
> author = "Hugo Authors"
> こんな感じに設定されてるけどよくわかんないよ

## title
> title = "Markdown Syntax Guide"
> これは記事のタイトル。hugo new をしたときと同じ名前にしておいたほうがいいよ

## data
> date = "2019-03-11"
> 日付だよ。今の自分の環境ではhugo newの時に自動でつくよ

## description
> これは概要っていうか記事の説明だよ
> description = "Sample article showcasing basic Markdown syntax and formatting for HTML elements."

## tags

> tags = [
>     "markdown",
>     "css",
>     "html",
>     "themes",
> ]
> 

## categories
> categories = [
>     "themes",
>     "syntax",
> ]

series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
image = "pawel-czerwinski-8uZPynIu-rQ-unsplash.jpg"
