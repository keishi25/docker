Dockerfileの使用方法
DockerFileを使用して、独自ページを表示させる
参考サイトhttps://qiita.com/mochizukikotaro/items/1d28888b78f401227ed6


１−１．Dockerfile内で、imageの選択
FROM nginx

１−２．Dockerfile内で、自作HTMLをコンテナ内にCOPYする
COPY ./html /usr/share/nginx/html

COPY はローカルファイルをコンテナの中にコピーするという、基本的な機能を持っている

２．imageの作成(nginx_testは、イメージ名）
$docker build --tag nginx_test .

