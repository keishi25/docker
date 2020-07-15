参考サイト　https://hub.docker.com/_/python

コマンド
Dockerfileからイメージの作成
１．$ docker build -t イメージ名 .

作成したイメージからコンテナ起動
２．$ docker run -it --rm --name コンテナ名 イメージ名

