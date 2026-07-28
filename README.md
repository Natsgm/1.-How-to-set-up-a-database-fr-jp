# 1.-How-to-set-up-a-database-fr-jp
Je décris comment commencer la base de donné facilement chez vous

**FR**


**JP**
**データベース(DB)インストール方法**

__ローカル開発__
データベース: MariaDB/MySQL
Apache: XAMPP
言語: SQL/php
管理アプリ: HeidiSQL
フレームワーク: laravelなど(無しでも可)

(わからない場合、YouTubeに転がってる初心者ガイドに頼るのがおすすめ)
1. 初心者の場合、データベースについてよく理解すること
2. [MariaDB](https://mariadb.org/) /[MySQL](https://www.mysql.com/jp/) などのDBをインストール
3. [XAMPP](https://www.apachefriends.org/jp/index.htmlhttps://www.apachefriends.org/jp/index.html) をインストール＆起動
4. HeidiSQLやDBをチェック
5. 作業開始

__サーバー開発__
管理アプリはHeidiSQLと[phpMyAdmin](https://www.phpmyadmin.net/) がおすすめ
Symfony/Laravelなどのフレームワークを使う場合、XAMPPより [Docker](https://www.docker.com/) を使うのがおすすめ

**DB基本**
データベース(DB): データを保存するシステム
XAMPP: Webや管理アプリなどの開発環境を整えるシステム
phpMyAdmin: DBの中身を管理するツール（テーブル作成、データ確認など）
フレームワーク: WebやアプリからDBのデータを保存・取得できるシステム。Laravel/Symphonyなどはその簡略化

映画表などの初心者ガイドを習得
DB用語を習得

__開発環境__
コンテナ型: 1つのOSの仮想できる箱 例: Docker メリット: 軽い
ハイパーバイザー型: 複数のOSの仮想マシン 例: hyper-V メリット: 重いが複数のOSを使用できる
※簡単に言うとVS code とVisual Studioの違いみたいな
