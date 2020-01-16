# maven
保持容器运行

# 使用
```
docker run \
    -dit --name maven \
    --restart=always \
    -v /srv/maven/setting.xml:/etc/maven/setting.xml \
    -v /srv/maven/.m2:/root/.m2 \
    hookbrother/maven
```