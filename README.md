# openapi-wallet-pass
外部提携用のパス発行webAPIの仕様をOpenApiで作成

## VScodeで表示

[Swagger Editor](https://editor.swagger.io/)
[VS code 拡張機能 OpenAPI (Swagger) Editor](https://qiita.com/tashinoso/items/ca38c669a80d14379f14)

1. opneapi.yaml を拡張機能で選択
2. 右上タブのプレビューアイコンを選択で、プレビューを表示（サーバー不要）

## Dockerで表示

opneapi.yaml と docker-compose.yml を作成してローカルで表示

[参考ページ](https://qiita.com/A-Kira/items/3d17396c7cc98873e29d)

## コード自動生成
```
# 対応生成コード表示
npm run og list
# コード生成
npm run og generate
```
### 参考ページ
[openapi-generator-cliでコード自動生成](https://zenn.dev/fumo/articles/233d82b796d489)

