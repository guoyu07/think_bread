think_bread
===============

这是一款基于 ThinkPHP 5.0 版本的类库，让我们能够轻松执行数据库 CURD 基本操作

 + 轻松实现数据库 CURD 操作
 + 支持查询条件功能

> 运行于 ThinkPHP5 及以上版本。


## 目录结构

初始的目录结构如下：

~~~
www  WEB部署目录（或者子目录）
├─application           应用目录
│  ├─index              index 模块目录（可以更改）
│  │  ├─controller      控制器目录
│  │    ├─Bread.php     BREAD 操作基类
│  │    ├─Index.php     入口控制器，继承自 Bread 
│  │  ├─model           模型目录
│  │  ├─view            视图目录
|
├─docs                  文档目录
│  ├─localhost.sql      测试数据表
|
|——README-THINK.md      thinkphp 文档
~~~

## 安装项目

1. 复制项目

`git clone git@github.com:huliuqing/think_bread.git`

2. 安装依赖

`composer install`

## ThinkPHP 5.0 项目运行
文档 [README-THINK](README-THINK.md)