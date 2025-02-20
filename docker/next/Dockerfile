# ベースイメージの指定
FROM node:lts-alpine

# 作業ディレクトリの指定
WORKDIR /var/www/html/app

# package.json と package-lock.json をコピー
COPY app/package.json app/package-lock.json ./

# 依存関係をインストール
RUN npm install

# ソースコードをコピー
COPY app ./

# 必要なパッケージをインストール
RUN apk add --no-cache git vim bash