# DEMO
ローカルホストでコンテナ内に起動したnode.jsにhttpアクセスするまで。

# How to run a container
 
```bash
git clone https://github.com/ISKroom/docker_first_project.git
cd docker_first_project
docker build -t iskroom/simpleweb .
docker run -p 8080:8080 iskroom/simpleweb
```

・この状態でブラウザから以下URLにアクセスすると「How are you doing」が表示される（Tagは何でもよい）  
・Windowsの場合は Docker Desktop の起動が前提

http://localhost:8080/

# 参考
https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/
