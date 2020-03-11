## 使い方


起動
```shell
$ docker-compose up -d 
```


ビルドしながら起動
```
$ docker-compose up -d --build
```

コンテナを消しながら止める
```shell
$ docker-compose down
```

コンテナは残して止める
```shell
$ docker-compose stop
```

## 詰まったところ

### PDOするとき

- パッケージのサポートがないといけないのでDockerfileに所定のパッケージを追加
- 接続先ホストをコンテナ名にしないといけない
- docker-compose-yml内にコンテナ名の指定はあった方が良い


### ヒアドキュメントが書けない

- 原因不明。避けた方が良い。

