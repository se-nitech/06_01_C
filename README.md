
# Dockerのgccサンプルコード

実行コマンド

```bash
docker pull gcc
docker build -t mygcc .
docker run -t --rm -v ${PWD}:/mnt mygcc gcc main.c
docker run -t --rm -v ${PWD}:/mnt mygcc ./a.out
```
