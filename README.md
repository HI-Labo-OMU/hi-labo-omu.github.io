---
layout: page
title: About
permalink: /about/
---
<!--
## Theme Monos
> Simple and lightweight theme for Jekyll

### Features
- Responsive.
- Syntax Highlight
- Most optimized theme for tech blog.
- Lightweight with minimum stylesheet.
- Easy to customize.
- Offers category menu.

### _config.yml
> Code block will look like this.
```yml
highlighter-theme: monokai //you can change your syntax color scheme.
date_format: "%Y-%M-%D" //and date format.
```

### Screenshots
#### Page
![alt text](/public/img/screenshot-1.png)
#### Articles
![alt text](/public/img/screenshot-2.png)
#### Page - Mobile
![alt text](/public/img/screenshot-m1.png)
#### Page - Articles
![alt text](/public/img/screenshot-m2.png)
-->

# 環境構築の手順
### ※既にGitのインストールとGitHubアカウントを作成済みであることを想定しています。まだの場合は以下を参照
- Gitのインストール：https://qiita.com/T-H9703EnAc/items/4fbe6593d42f9a844b1c
- GitHubアカウントの作成：https://github.com/

## 1. Rubyのインストール
参考：https://prog-8.com/docs/ruby-env-win
「①Rubyのインストール」まで．現在，バージョン3.1.4以前でしか動かないようです．インストールする際は，これ以前のバージョンをインストールしてください．

## 2. GCCのインストール
参考：https://www.javadrive.jp/cstart/install/index6.html

## 3. Makeのインストール
参考：https://www.kkaneko.jp/tools/win/make.html

## 4. Jekyllのインストール
コマンドプロンプトにて，`gem install jekyll bundler `を実行する．
`jekyll -v`でバージョン情報が出力されれば，インストールされている．
参考：https://jekyllrb-ja.github.io/docs/installation/windows/

## 5. GitHib PagesにてJekyllを使用できるように設定
### 5.1 ローカルにmasterブランチをpull
### 5.2 コマンドプロンプトにて，`bundle install`を実行する．

以上で環境構築は終了です．`bundle exec jekyll serve`を実行することによりサーバが起動し，「http://127.0.0.1:4000/」でサイトを閲覧できます．
Jekyllの使い方については，[こちら](https://e-joint.jp/blog/329)を参考にしてください．

