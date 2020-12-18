# How to use it

> 1.  install docker from the link below <br /> > https://docs.docker.com/compose/install/
> 2.  start docker by the following command
>
> ```shell
> docker-compose up -d
> ```
>
> 3.  Access to the URL on browser <br /> >
>     http://localhost:8080/ or http://127.0.0.1:8080/
> 4.  When stopping docker, use
>
> ```shell
> docker-compose down
> ```

# How to upload local files and make it work on serveer(Sakura rental server)

> https://yuruyururoad.jp/2017/09/30/mampwordpress/

# 使い方

> 1.  docker を下記からインストール <br /> > https://docs.docker.com/compose/install/
> 2.  下のコマンドで docker を開始する
>
> ```shell
> docker-compose up -d
> ```
>
> 3.  下の URL からローカルで作成した WordPress にアクセスできる <br /> >
>     http://localhost:8080/ or http://127.0.0.1:8080/
> 4.  Docker を止めるときは下記コマンドを使用
>
> ```shell
> docker-compose down
> ```

# 本番環境へのアップロード

> https://yuruyururoad.jp/2017/09/30/mampwordpress/

# Note

## Set up Docker-Comopose

> https://qiita.com/tomokei5634/items/75d2501cfb968d0cfab5

## For troubleshooting

### Docker Command

```shell
# Show comntainer images
docker images
# Remove comntainer images
docker rmi xxx
# Show running containers (for all use -a)
docker ps
# remove all containers
docker rm $(docker ps -aq)
# stop all containers
docker stop $(docker ps -aq)
```

### Shell Command

```shell
# Show PID so you can open a port
lsof -i:8080
# Kill PID
kill xxx
```
