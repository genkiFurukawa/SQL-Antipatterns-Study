# SQLアンチパターン 勉強用リポジトリ
## 起動方法と接続方法
下記のコマンドを実行する。

```
$ cd {docker-compose.ymlが配置してあるディレクトリ}
$ docker-compose up
```

別のターミナルで下記のコマンドを実行する。

```
$ mysql -u root -p -h 127.0.0.1 -P 3314
```