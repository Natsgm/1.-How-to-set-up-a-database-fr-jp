# 1.-How to set up a database fr/jp
Je décris comment commencer la base de donné facilement chez vous

**FR**
**Comment installer une base de données (DB)**

**Développement local**
Base de données : MariaDB/MySQL
Apache : XAMPP
Langages : SQL/PHP
Application de gestion : HeidiSQL
Framework : Laravel, etc. (facultatif)

(Si vous ne savez pas comment faire, il est recommandé de vous aider d'un guide pour débutants disponible sur YouTube.)

1. Si vous êtes débutant, commencez par bien comprendre les bases de données.
2. Installez une base de données comme [MariaDB](https://mariadb.org/) / [MySQL](https://www.mysql.com/jp/), etc.
3. Installez et démarrez [XAMPP](https://www.apachefriends.org/jp/index.html).
4. Vérifiez HeidiSQL et la base de données.
5. Commencez à travailler.

**Développement côté serveur**
Pour les applications de gestion, HeidiSQL et [phpMyAdmin](https://www.phpmyadmin.net/) sont recommandés.

Si vous utilisez un framework comme Symfony/Laravel, il est recommandé d'utiliser [Docker](https://www.docker.com/) plutôt que XAMPP.

**En bonus**

**Les bases de la DB**
Base de données (DB) : système permettant de stocker des données.
XAMPP : système permettant de préparer un environnement de développement pour le Web, les applications de gestion, etc.
phpMyAdmin : outil permettant de gérer le contenu d'une base de données (création de tables, vérification des données, etc.).
Framework : système permettant à un site Web ou à une application d'enregistrer et de récupérer des données dans une base de données. Laravel/Symfony, etc., permettent de simplifier ce processus.

Apprendre un guide pour débutants, comme celui sur la création d'une table de films.
Apprendre le vocabulaire lié aux bases de données.

**Environnements de développement**
Type conteneur : une « boîte » virtuelle qui permet de faire fonctionner un environnement isolé sur un seul système d'exploitation. Exemple : Docker. Avantage : léger.
Type hyperviseur : plusieurs machines virtuelles permettant d'utiliser différents systèmes d'exploitation. Exemple : Hyper-V. Avantage : plus lourd, mais permet d'utiliser plusieurs systèmes d'exploitation.

※ Pour faire simple, c'est un peu comme la différence entre VS Code et Visual Studio.


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


**おまけ**

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
