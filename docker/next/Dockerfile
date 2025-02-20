# ベースイメージの指定
FROM node:lts-alpine

# 作業ディレクトリの指定
WORKDIR /var/www/html

# 必要なパッケージをインストール
RUN apk add --no-cache git vim bash \
    && npm install -g create-react-app