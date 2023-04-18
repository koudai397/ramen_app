# ラーメンアプリ
このアプリは、お気に入りのラーメン店を登録し管理することができます。<br>初めてAPIを使用してアプリを作成しました。

### 概要
* ラーメン店の登録・編集・削除  
* 登録したラーメン店の一覧表示  
* 登録したラーメン店の地図表示  

### デモ
https://user-images.githubusercontent.com/111045383/232701068-00abf5dd-9918-4f28-aadf-f4b2eb35e781.mp4



### インストール方法
1. このプロジェクトをクローンします。
2. 必要なgemのインストール
```console
$ bundle install
```
3. データベースをセットアップ
```
$ rails db:migrate
```
4. アプリの起動
```
$ rails server
```

## 使い方
1. トップページから新規登録をします。
2. 住所を入力し、「住所を検索する」ボタンをクリックします。
3. 地図が表示され、地図上でラーメン屋の場所をクリックします。
4. 登録ボタンをクリックして、ラーメン屋を登録します。
5. マイページから、登録したラーメン屋の詳細情報を確認できます。


### ライブラリ
このアプリは以下のライブラリを使用しています。
* Google Maps JavaScript API

