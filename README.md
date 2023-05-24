### 依赖
docker pull nginx

### 启动/重启镜像
git pull origin master
docker rmi -f web-test 
docker build -t web-test . 
docker-compose up -d web-test

### 进入镜像
docker exec -i -t nginx /bin/bash

