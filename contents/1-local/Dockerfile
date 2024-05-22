# 基本イメージを指定
FROM ubuntu:20.04

# Nginxをインストール
RUN apt-get update && apt-get install -y nginx

# このコンテナが外部に公開したいポート番号（ドキュメントのような役割）
EXPOSE 80

# ホストのindex.htmlをコンテナにコピー
COPY ./index.html /var/www/html/index.html

# コンテナ実行時のデフォルトコマンドを指定。
# 端末からの入力を受け付ける状態になっているプロセスグループのことをフォアグラウンドプロセスという

下記コマンドは
CMD ["nginx", "-g", "daemon off;"]