# docker
docker 基本コマンド

イメージの確認
```
$docker images
```

コンテナのstatus確認＆一覧表示
```
$ docker ps -a
```
コンテナの削除
```
$docker rm コンテナID
```

コンテナの停止
```
$docker stop コンテナID
```

コンテナ内にログイン
```
$docker exec -it コンテナ名 /bin/bash
```

Dockerfileのコマンド解説
https://tech-lab.sios.jp/archives/19191
