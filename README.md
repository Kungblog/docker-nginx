# 关于本镜像

这是利用[nginx](https://registry.hub.docker.com/_/nginx/)官方Git repo的Docker镜像，由Kung修改用于反向代理后端服务器.
如果需要使用本镜像，您需要自己设置Nginx的配置文件.

#修改配置文件

RUN cd /etc/nginx && wget http://tpver54-pbcgeter.daoapp.io/nginx.conf //将本条内容中wget的文件改成您修改过的Nginx配置文件.

本程序支持在国内DaoCloud的Docker虚拟机上部署,也可以在其他的Docker虚拟机上部署.
※DaoCloud不支持使用SSH管理!

#其他信息

基于debian:jessie 运行Nginx 1.9.4-1 没有SSH服务器.
