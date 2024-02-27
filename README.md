# Rubyでmecabを使う

## 環境構築
- イメージ作成
```
docker compose build
```
- コンテナ起動
```
docker compose up -d
```
- お試し実行
```
docker compose exec app bash
ruby sample.rb
```

## メモ
- 実環境でのパスなどは調整する必要があるかもしれない
