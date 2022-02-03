# アプリケーション名
Beginner Chat

# アプリケーションの概要
未経験で挑戦を始める人達のチャット場。同じ未経験同士で挑戦や失敗なども共有できる場。

# URL
https://beginnerchat-app-37236.herokuapp.com/

# テスト用アカウント
・Basic認証ID shohei

・BasicBasic認証ID 4126

・メールアドレス（テスト）hoge@hoge.com

・Password S111111

# 利用方法

## チャット投稿
1.ログイン後に「チャットを作成」で新規ルームの作成。

2.新規チャットルーム作成ページで「チャットルーム名」と「チャットメンバー」を記入と選択後にCreate Roomを押す。

3.ルーム作成後は、マイページの作成ルームで、Chatでテキスト、画像、マークダウン（シンタックスハイライト適用）を入力し投稿。

## 未経験同士で情報共有
1.未経験で始めた事をルーム内でテキスト、画像など情報交換する。

2.なるべくシンプルな機能ボタンで気軽に情報共有。

3.マークダウン記法などを練習しながら、コードを共有。

## アプリケーションを作成した背景
未経験で新しい事に挑戦する人たちの不安などを共有できる場があると良いなと思いBeginnerChatを作りました。
なぜなら、スクールで学習を行った際に、未経験同士であれば、エラーが発生する箇所や理解できる表現の仕方が同じなど共感点があったため、なるべくシンプルにチャットに触れられる機会が必要だと思ったからです。

# 洗い出した要件
https://docs.google.com/spreadsheets/d/1gC1yDwk5P-zaKh1hxuzptEAOKWCwJcyJJeue57bQHq0/edit#gid=982722306

# 実装した機能についての画像やGIFおよびその説明
チャットルームごとにテキスト投稿、画像投稿が出来ます。その他にマークダウン記法とシンタックスハイライト適用でコードの共有。
[![Image from Gyazo](https://i.gyazo.com/33d21e811e55c649742cef32cb3c3e69.gif)](https://gyazo.com/33d21e811e55c649742cef32cb3c3e69)

# テーブル設計

[![Image from Gyazo](https://i.gyazo.com/0ead2859c5f7e054331ac8f233563025.png)](https://gyazo.com/0ead2859c5f7e054331ac8f233563025)

# 画面遷移図

[![Image from Gyazo](https://i.gyazo.com/7e15365bc6022bdd2fe9c13900f76790.png)](https://gyazo.com/7e15365bc6022bdd2fe9c13900f76790)

# 開発環境
・フロントエンド

・バックエンド

・インフラ

・テスト

・テキストエディタ

・タスク管理

# ローカルでの動作方法

以下のコマンドを実行

% git clone https://github.com/itosyo-takumi/beginnerchat-app.git

% cd itosyo-takumi/beginnerchat-app.git

% bundle install

% yarn install

# 工夫したポイント
1.シンプルで使いやすいようにボタンも少なく、チャット作成を意識しました。

2.gitのプロジェクトボードを使って、機能ごとに進捗管理をしました。

3.コードの共有でシンタックスハイライトが適用されるようにしました。
