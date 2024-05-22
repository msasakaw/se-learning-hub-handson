# FROM：OSなどのベースとなるイメージを指定
# Dockerfile for WordPress
FROM wordpress:latest

# ENV：環境変数設定のためのコマンド
# WordPressとMySQLの接続情報
ENV WORDPRESS_DB_HOST 127.0.0.1:3306
ENV WORDPRESS_DB_USER wordpress_user
ENV WORDPRESS_DB_PASSWORD wordpress_password
ENV WORDPRESS_DB_NAME wordpress

# EXPOSE：ポートの開放を記述
EXPOSE 80