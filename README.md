# 開発環境の作り方

開発環境の構築に Docker を使用しています。

以下のコマンドを実行

```
$ docker-compose build
$ docker-compose run --rm rails yarn install
$ docker-compose run --rm rails ./bin/setup
```

プロセスの起動
```
$ docker-compose up rails

あるいは
$ docker-compose up -d
```

