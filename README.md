# percona 在线实验环境

## 软件简介

Percona Server是由Percona创建的MySQL关系数据库管理系统的一个分支。

它旨在保持与官方MySQL版本的密切兼容性，同时专注于性能和增加对服务器操作的可见性。Percona服务器中还包含了Percona的InnoDB存储引擎的XtraDB

所属类别是数据库

特点：

1.Percona Server 只包含 MySQL 的服务器版，并没有提供相应对 MySQL 的 Connector 和 GUI 工具进行改进

2.Percona Server 使用了一些 google-mysql-tools, Proven Scaling, Open Query 对 MySQL 进行改造

## 软件官网

https://www.percona.com/

## Dockerfile 使用方法

启动percona服务器实例

启动Percona实例很简单：
```
$ docker run --name some-percona -e MYSQL_ROOT_PASSWORD=my-secret-pw -d percona:tag
```
some-percona您要分配给容器的名称是要为my-secret-pwMySQL root用户设置的密码，是指定tag所需MySQL版本的标签
## 资源链接

- https://hub.docker.com/_/percona/
- https://www.percona.com/software/documentation
