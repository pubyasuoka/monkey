# How to use
## 起動
```
docker-compose build
docker-compose up -d
```
## 実行
```
docker-compose exec app go run main.go
# docker-compose exec サービス名 コマンド
```
```
docker-compose exec app /bin/bash # コンテナのシェル起動
go run main.go
```