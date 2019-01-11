# Docker-Cache-Intersystems 
Caché Intersystens in Docker Container

本工程fork自https://github.com/tiagogribeiro/cache-intersystems-docker

https://hub.docker.com/r/tiagoribeiro/cache-database/

# 版本信息
2016.2.1.803

# 安装步骤

- 需要提前安装好docker和docker-compose工具

- 修改docker-compose.yml文件，调整网络地址为你本机所在的网络

- 启动服务
$ docker-compose up

- 访问服务
使用如下地址访问：
http://服务IP地址/csp/sys/utilHome.csp


