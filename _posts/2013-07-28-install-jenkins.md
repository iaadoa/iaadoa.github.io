---
layout: post
title: Jenkins学习笔记——安装
---

安装超简单：

1.去官网下载系统对应的安装包，我主要用RedHat/CentOS的，偶尔用一下Windows的；

2.CentOS下rpm -Uvh jenkins-XXXXX.rpm

3.Windows下setup.exe

4.当然也可以下一个war，用JRE直接运行

需要注意的是CentOS上安装之后默认创建了一个jenkins用户，但是这个用户不能SSH登录，jenkins的默认目录是/var/lib/jenkins。
