# sample flyway
## DBコンテナ起動
```
docker-compose up -d db
```

## マイグレーション
```
docker-compose run --rm flyway-migrate
```

## マイグレーション履歴
```
docker-compose run --rm flyway-info
```

## データベース上の全テーブル削除
```
docker-compose run --rm flyway-clean
```

## マイグレーション失敗時の修復
```
docker-compose run --rm flyway-repair
```
