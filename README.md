# DEMO
ローカルホストでコンテナ内に起動したnode.jsにhttpアクセスするまで。

# How to run a container
 
```bash
git clone https://github.com/ISKroom/docker_first_project.git
docker built -t <docker id>/<project name> .
docker run -p 8080:8080 <docker id>/<project name>
```

この状態でブラウザから以下URLにアクセスすると「How are you doing」が表示される。
http://localhost:8080/

# 参考
https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/
