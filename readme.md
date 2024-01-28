# API開発 01

## 更新日：2024-01-28

## 概要

API開発を試す環境

## コマンド一覧

### docker関係

```sh
# docker-composeの起動
docker compose up -d

# フロントエンド環境のターミナルに接続
docker-compose exec -it frontend bash

# バックエンド環境のターミナルに接続
docker-compose exec -it backend bash

# コンテナの起動確認
docker ps

# docker-composeのエラー確認(コンテナが立ち上がらないときなど)
docker compose logs

# docker-composeの削除
docker compose down
```

### backend関係

``` sh

# バックエンドサーバ開始
python manage.py runserver 0:8000 --settings dev_django.settings.development

```

