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
1. docker-composeで立ち上げ
1. dockerのコンテナ内に入る
1. laravelの立ち上げ
1. http://localhost:8000 にGUIでアクセス

```bash

git clone https://github.com/kazun1224/laravel_management_system.git

cd "directory name"
docker-compose up -d

docker-compose exec app bash
cd management_system
php artisan serve

```
