# DevelopmentEnvironmentByCodeServer
code-serverで開発環境を構築する。

## 起動コマンド

```
docker run -it -p 127.0.0.1:8080:8080 \
  -v "$PWD:/home/coder/project" \
  -u "$(id -u):$(id -g)" \
  codercom/code-server:3.8.0
```

## 参考

- [Docker hub:codercom/code-server](https://hub.docker.com/r/codercom/code-server)
