# Nginx + PHP + MySQL Docker コンテナ

このリポジトリは、サーバ(PHP + MariaDB）の Docker コンテナを含む、プッシュ通知入力・送信システムのサンプルコードです。

サーバーの起動は以下のコマンド：
```console
docker-compose up -d
```

./php/src 内の config.php.example を config.php Firebase のサーバーキーを記載する。

Web アプリは、以下のアドレス（Docker Toolbox でコンテナを起動した際の例）にアクセスする。
```
http://192.168.99.100/
```
