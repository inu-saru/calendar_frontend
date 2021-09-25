# 環境構築
```
$ docker-compose build
$ docker-compose up -d
```

## シェル
```
$ docker-compose exec -it calendar_frontend sh
```

## webサーバー起動
```
# vue起動
app$ npm run dev
```

## vue install
```
# vueインストール
app$ vue init webpack
# 以降全部エンターでインストール開始
```

## lint
```
# 確認
npm run lint
# 自動修正
npm run lint -- --fix
```