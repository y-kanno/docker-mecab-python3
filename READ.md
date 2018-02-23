# docker-mecab-python3
mecab-python3の開発環境コンテナ（個人用.ubuntuベース）
docker-machine,docker-composeがインストールされている前提。

dockerイメージ自体はこちら
https://hub.docker.com/r/ykanno/docker-mecab-python3

# how to use
```
$ docker-machine create MACHINE_NAME --driver virtualbox --virtualbox-disk-size "30000"
$ git clone https://github.com/y-kanno/docker-mecab-python3
$ docker-compose build
$ docker-compose up -d
$ docker exec -it CONTAINER_NAME bash
```

あとはpythonリポジトリをcloneするなりよしなに。
