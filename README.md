

[docs/docs/serving/samples/hello\-world/helloworld\-kotlin at mkdocs · knative/docs](https://github.com/knative/docs/tree/mkdocs/docs/serving/samples/hello-world/helloworld-kotlin)

[Docker \| Ktor](https://ktor.io/docs/docker.html#getting-the-application-ready)



## 0 クリーンアップ

ボリュームも消す時は以下

```
docker-compose down --volumes
```

```
./gradlew installDist
```

## 2. up

```
docker-compose up

docker-compose up --build
```


## dockerの中に入るコマンド


- logstash

```
docker exec -i -t logstash bash
```

