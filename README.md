# 自動販売機の売り上げ管理システム

larabaelで作成した管理システム

# Requirement

- docker
- docker-compose
- php
- larabel
- mylsql
- phpadmin


# Usage

アプリの立ち上げ
1. ソースコードをクローン
2. docker-composeで立ち上げ
3. dockerのコンテナ内に入る
4. management_systemのディレクトリに移動
5. .envファイルを作成して.env.exampleをコピーして記述後に、dbの設定を追記
6. APP_KEYを設定
7. composer install & npm install でpackageをインストール
1. laravelの立ち上げ
1. http://localhost:8000 にGUIでアクセス

```bash

git clone https://github.com/kazun1224/laravel_management_system.git

cd "directory name"
docker-compose up -d

docker-compose exec app bash
cd management_system
php artisan key:generate
composer install
npm install
php artisan serve

```
