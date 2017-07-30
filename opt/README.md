# Apache＋PHP5.6 Server - Debian

docker-composeコマンドを使っての操作方法を記載します。

## 起動方法について（ RUN ）

下記のコマンドにてコンテナを起動します。 (port 80 is available)

```
$ git clone git@bitbucket.org:reflet/server-debian8-httpd-php56.git .
$ cd docker
$ docker-compose up -d
```

コンテナの起動状況は下記コマンドにて確認ください。

```
$ docker-compose ps
```

## テストについて（ TEST ）

下記コマンドにて、結果が返ってきたら問題ありません。

```
$ curl http://localhost/
```

## メンテナンスについて（ EXEC ）

コンテナ内に入って操作したい場合は、下記コマンドにて接続ください。

※操作を終了する場合は、「exit」でコンソールを抜けられます。

```
$ docker exec -u "www-data" -it php /bin/bash
```
