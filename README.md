
# Dockerのgccサンプルコード

実行コマンド

```bash
docker pull gcc
docker build -t mygcc .
docker run -it --rm -v ${PWD}:/mnt mygcc gcc main.c
docker run -it --rm -v ${PWD}:/mnt mygcc ./a.out
```
