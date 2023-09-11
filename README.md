# Grafana 中文教程

文本教程原文发布在：https://kalacloud.com/blog/grafana-with-prometheus-tutorial/


## 什么是 Grafana 
Grafana 是由 Grafana Labs 开发的开源监控监控系统，你可以用它来监控线上系统，极大地简化运维和开发工作。

它不对数据源作假设，因此你可以用包括 Prometheus, MySQL 在内的任何（时序）数据库搭配使用。

## 如何启动 Grafana

请 clone 本教程代码，然后确认本地已经安装 docker-compose 后，在本目录运行

`docker-compose up` 

这条命令会启动三个 docker 容器，包括

`prometheus`, `service` 和 `grafana` 

其中 `prometheus` 是普罗米修斯时序数据库

`service` 是普罗米修斯自带的数据生成器（监控本机 CPU 内存等信息）

`grafana` 就是 Grafana 服务本身

## 访问 localhost:3000

在你的浏览器中访问 `localhost:3000` 即可看到运行的 Grafana，再根据教程中的步骤设置好源即可

## 下一步

请继续关注卡拉云博客，在之后的文章中我们将继续介绍如何用 Prometheus 实现监控具体的服务，如何用 PromQL 等


