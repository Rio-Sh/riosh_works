---
title: "Quick Wordbook"
date: 2022-03-06T20:05:48+09:00
summary: English vacabulary wordbook app for Android
draft: false
cover:
    image: "images/quick_thumb(1).png"
---

**English vocabulary wordbook app**

{{< video src="wordbook_demo" height="400px" >}}
  
### 概要
簡単に単語を追加できる英単語帳アプリ。  
翻訳にGoogle Apps Scriptとの通信を用いるバージョンと、ローカルでMLkitを用いるバージョンがあります。  
  
### github repository
[Rio-Sh/QuickWordbook](https://github.com/Rio-Sh/QuickWordbook)  

### Apk file
[quickwordbook-release.apk](/apk/quickwordbook-release-ver1_1.apk)  
※最新のリポジトリを反映していない場合があります。

MlKitを使用したバージョン  
 [quickwordbook-release_mlkit.apk](/apk/quickwordbook-release_mlkit.apk)
  
### 機能
* 単語の追加・削除・編集
* 単語の追加編集時の自動翻訳(英訳・和訳)
* 追加した単語の一覧表示
* ダークモード対応
{{< video src="wordbook_dark_demo" height="250px" >}}　　
* 翻訳する言語の自動識別(※Mlkitを使用したバージョンのみ)
  

### 主な使用技術やライブラリ
* 単方向データフロー(UDF)
* Jetpack Compose
* Retrofit
* Room
* Kotlin Coroutine
* Hilt
* JUnit
