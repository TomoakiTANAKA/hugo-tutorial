+++
date = "2017-06-18T12:12:41+09:00"
draft = true
title = "テーマを適用する"
+++

# テーマのインストール

基本的に、テーマをgithubから取ってきて配置するだけでよい。

```
cd theme
git clone https://github.com/dim0627/hugo_theme_robust.git

# ホームへ戻って、実行する
# -t or --theme でテーマを指定する
cd ..
hugo server --theme=hugo_theme_robust --buildDrafts
hugo server -t hugo_theme_robust --buildDrafts
```

