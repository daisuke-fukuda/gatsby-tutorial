# ベースイメージを指定
FROM node:10.15-alpine

# node.js の環境変数を定義する
# 本番環境では production
ENV NODE_ENV=development

RUN apk add git curl

RUN npm install -g gatsby-cli surge


# ディレクトリを移動する
WORKDIR /app


# ポート8000番を開放する
EXPOSE 8000