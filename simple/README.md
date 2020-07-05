docker 基礎コマンド
参考サイト
https://qiita.com/mtakehara21/items/d7be42cf12772f3ada25

１．nginx imageの取得
$dokcer pull nginx

２．コンテナ起動
（nginxコンテナ起動の場合は、引数にポート番号を指定する）
$docker run --name hogehoge -d -p 8080:80 nginx


