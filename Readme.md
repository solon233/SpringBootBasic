# SpringBootの基本的な実装サンプル

## 概要
入門書などでSpringBootの実装方法などが解説されているが<br>
とりあえず動かせるサンプルがないと学習も進まないと思いますのでサンプルを提供します<br>

主に以下の学習を目的としたサンプルです
<ul>
<li>SpringBootフレームワークの使用方法</li>
<li>Tymeleafの使用方法</li>
<li>MyBatisの使用方法</li>
<li>サーバ起動時にh2を起動する方法</li>
<li>データベースからデータ取得方法</li>
<li>取得したデータを画面に表示する方法</li>
</ul>

## 開発環境
Eclipse IDE for Java Developers (includes Incubating components)<br>
Version: 2023-09 (4.29.0)<br>
Build id: 20230907-1323

## システム構成
Java17<br>
maven<br>
SpringBoot 3.0.2<br>
・tymeleaf（テンプレートエンジン）<br>
・MyBatis（ORマッパー）<br>
h2（データベース）<br>

※バックエンドのシステムのみで動作するようにしています

## 起動方法
・mavenで"install"を実行してビルドする<br>
・Eclipseの"Bootダッシュボード"でSpringBootをサーバ起動<br>
・Choromeなどのブラウザで"http://localhost:8080"を表示<br>
