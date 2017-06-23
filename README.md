amazonlinux-nginx-flask
====

Dockerを使い、Amazon Linux+Nginx+uwsgi+Flaskで環境を構築しています

## Description
本イメージは、Flaskでアプリケーションを作る土台となっています。
TensorFlowなどのアプリケーションを実行する土台とすることができます。

## Usage
git clone https://github.com/gelehrtecrest/amazonlinux-nginx-flask.git
cd amazonlinux-nginx-flask
docker build -t gelehrtecrest/amazonlinux-nginx-flask .
docker container run -itd -p 80:8080 gelehrtecrest/amazonlinux-nginx-flask

## Test
ブラウザでhttp://localhost にアクセスしてください。
