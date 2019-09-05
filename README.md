## Docker学习文档

* #### 虽然我知道，大部分人都是来了直接下载笔记后就潇洒的离开，并且只有等到要用的时候才突然想到“我的天~~我得去学学docker”的时候才会重新来到这儿，写得不好，希望大家多多包含


* [简介]
    * [常用的docker容器命令](Docker常用容器命令.md)
    * [Centos常用知识](Centos常用命令.md)
    * [Java常用知识](常用知识/Java常用知识.md)
    * [Linux系统安装docker]
        * [Linux安装docker]
            * [Linux通用脚本在线安装最新版的docker](docker,compose,swarm的安装/linux安装docker/Linux通用脚本在线安装.md)
            * [Centos7通过安装包安装18.03和18.09版本](docker,compose,swarm的安装/linux安装docker/Centos7通过安装包安装docker.md)
            * [Ubuntu16.04通过安装包安装18.03和18.09版本](docker,compose,swarm的安装/linux安装docker/Ubuntu16.04通过安装包安装docker.md)
        * [批量创建虚拟机]
            * [docker-machine批量创建boot2docker虚拟机](docker,compose,swarm的安装/docker-machine搭建swarm集群/shell/create-wms.sh)
            * [vagrant批量创建虚拟机的Vagrantfile脚本](vagrant/multi/Vagrantfile)
        * [docker-swarm集群搭建]
            * [docker镜像搭建docker集群](docker,compose,swarm的安装/docker镜像搭建docker集群/docker镜像搭建docker集群.md)
            * [docker-machine创建docker-swarm集群](docker,compose,swarm的安装/docker-machine搭建swarm集群/docker-machine创建docker-swarm集群.md)
            * [vagrant制作docker的虚拟机模板](vagrant/制作vagrant系统镜像/虚拟机vagrant模板的制作.md)
            * [docker-swarm集群的讲解](docker,compose,swarm的安装/docker-swarm集群的讲解.md)
    * [vagrant]
        * [使用说明](vagrant/使用说明.md)
        * [常用命令](vagrant/vagrantvagrant常用命令.md)
        * [Centos的vagrant模板的制作](vagrant/制作vagrant系统镜像/Centos的vagrant模板的制作.md)
            * [Centos-1804可远程登录的模板](vagrant/制作vagrant系统镜像/CentOS/CentOS-7-x86_64-Vagrant-1804_02.VirtualBox-直接粘贴就可以运行.md)
            * [Centos-1805可远程登录的模板](vagrant/制作vagrant系统镜像/CentOS/CentOS-7-x86_64-Vagrant-1805_01.VirtualBox-直接粘贴就可以运行.md)
            * [Centos-1811可远程登录的模板](vagrant/制作vagrant系统镜像/CentOS/CentOS-7-x86_64-Vagrant-1811_02.VirtualBox-直接粘贴就可以运行.md)
        * [Ubuntu的vagrant模板的制作](vagrant/制作vagrant系统镜像/Ubuntu的vagrant模板的制作.md)
            * [Ubuntu-1804可远程登录的模板](vagrant/制作vagrant系统镜像/Ubuntu/Ubuntu-18.04-bionic-server-cloudimg-amd64-vagrant-直接粘贴就可以运行.md)
            * [Ubuntu-1811可远程登录的模板](vagrant/制作vagrant系统镜像/Ubuntu/Ubuntu-18.10-cosmic-server-cloudimg-amd64-vagrant-直接粘贴就可以运行.md)
    * [软件的使用和部分的镜像制作]
        * [chrony时间同步工具](常用软件/chrony/chrony时间同步工具.md)
        * [calico使用命令](常用软件/calico/calico.md)
        * [node使用命令](常用软件/node/node命令.md)
        * [nginx]
            * [参数说明](常用软件/nginx/参数说明/nginx.conf配置文件参数自定义划分为三类.md)
            * [docker-compose创建nginx请求转发的例子](常用软件/nginx/example001/docker-compose.yml)
            * [在阿里云控制台web页面设置域名与公网IP的映射](常用软件/nginx/在阿里云控制台web页面设置域名与公网IP的映射.md)
            * [ssl证书申请](常用软件/nginx/申请证书/ssl证书申请.md)
        * [cfssl生成证书的命令说明](常用软件/cfssl/详细说明.md)
            * [cfssl给nginx生成 通配所有IP和域名的证书 ](常用软件/cfssl/all-ip-domain-通配所有IP和域名的证书.md))
            * [添加cfssl给nginx生成自签名证书的例子](常用软件/cfssl/nginx-examples/example001/README.md)
        * [etcd命令](常用软件/etcd/etcd命令.md)
        * [draw.io镜像制作的Dockerfile文件](常用软件/draw.io/dockerfile/Dockerfile)
        * [easy-mock镜像制作的Dockerfile文件](常用软件/easy-mock/Dockerfile/Dockerfile)
        * [gopub使用命令](常用软件/gopub/README.md)
        * [etcd软件使用的命令](常用软件/etcd/etcd命令.md)
        * [shell命令行操作json的工具-jq](常用软件/shell命令行操作json的工具-jq/使用说明.md)
        * [shell命令行操作xml的工具-xmlstarlet](常用软件/shell命令行操作xml的工具-xmlstarlet)
        * [nexus3仓库的配置](仓库/搭建本地仓库/nexus3/nexus3.md)
        * [squid的配置](常用软件/squid/squid.md)
        * [brew安装软件](常用软件/brew/README.md)
        * [jhipster命令](常用软件/jhipster/jhipster命令.md)
        * [shadowsocks]()
            * [shadowsocks命令参数](常用软件/shadowsocks/shadowsocks.md)
            * [shadowsocks的真实示例](常用软件/shadowsocks/真实示例.md)
        * [curl工具的使用](常用软件/curl/curl使用.md)
        * [keycloak开源的单点登录系统]()
        * [centos7开启telnet远程登录](常用软件/telnet/telnet使用.md)
        * [zookeeper](常用软件/zookeeper/README.md)
            * [单节点](常用软件/zookeeper/singleNode/README.md)
        * [ELK]
            * [elasticsearch]
                * [elasticsearch单节点部署情况](常用软件/elk/elasticsearch/single-node/README.md)
                * [es集群搭建](常用软件/elk/elasticsearch/multi-nodes/集群搭建.md)
                * [elasticsearch的restful接口讲解](常用软件/elk/elasticsearch/各种restful接口命令讲解/README.md)
                * [elasticsearch备份工具](常用软件/elk/elasticsearch/elasticsearch备份工具.md)
    * [数据库]
        * [NOSQL]
            * [mongo]
                * [mongo常用命令](数据库/NOSQL/mongo/mongo常用命令.md)
                * [mongo备份还原](数据库/NOSQL/mongo/mongo备份还原.md)
            * [neo4j的学习](数据库/NOSQL/neo4j/neo4j学习.md)
            * [Redis]
                * [redis博客](数据库/NOSQL/redis/Redis博客.md)
                * [Redis命令](数据库/NOSQL/redis/Redis命令.md)
                * [Redis-cluster集群搭建](数据库/NOSQL/redis/Redis-cluster集群搭建.md)
                * [Redis-trib的常用命令](数据库/NOSQL/redis/Redis-trib的常用命令.md)
                * [Redis性能压测工具redis-benchmark](数据库/NOSQL/redis/性能压测工具redis-benchmark.md)
        * [SQL]
            * [postgresql命令](数据库/SQL/postgresql/postgresql命令.md)
            * [mysql命令](数据库/SQL/mysql/mysql命令.md)
            * [mysql的多主集群Percona-XtraDB-Cluster的介绍](数据库/SQL/mysql/Percona-XtraDB-Cluster/README.md)
            * [mysql的多主集群Percona-XtraDB-Cluster的docker-compose脚本](数据库/SQL/mysql/Percona-XtraDB-Cluster/手动加入集群方式/docker-compose.yml)
            * [mysql的多主集群Percona-XtraDB-Cluster的docker搭建](数据库/SQL/mysql/Percona-XtraDB-Cluster/集群创建的命令.md)
    * [网络]
        * [ssh内网穿透]
            * [例子1](网络/ssh内网穿透/场景1/内网穿透.md)
            * [例子2](网络/ssh内网穿透/场景2/内网穿透.md)
    * [运维]
        * [ansible]
            * [ansible入门例子](运维/ansible/入门例子/README.md)
            * [ansible线上环境实战任务](运维/ansible/example01/任务.md)
        * [jenkins]
            * [jenkins的使用](运维/jenkins/使用说明.md)
    * [linux]
        * [alpine的安装.md](仓库/linux/alpine/alpine的安装.md)
        * [Linux的磁盘挂载.md](常用知识/Linux的磁盘挂载.md)
    * [预留模块]
        * [大数据]
            * [docker搭建真正的Hadoop集群](预留模块/大数据/hadoop/Hadoop搭建.md)
    * [systemd开机服务设置参数](零散的笔记/systemd开机服务设置参数.md)
    * [各种Linux系统配置国内软件源加速器](https://t.goodrain.com/t/topic/236)
        * [alpine国内软件源仓库配置](仓库/各种Linux系统的国内软件源仓库/alpine.md)
        * [debian国内软件源仓库配置](仓库/各种Linux系统的国内软件源仓库/debian.md)
        * [ubuntu国内软件源仓库配置](仓库/各种Linux系统的国内软件源仓库/ubuntu.md)