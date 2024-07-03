# 基于Java的商城网站系统设计与实现


### 功能介绍

平台采用B/S结构，后端采用主流的Springboot框架进行开发，前端采用主流的Vue.js进行开发。

整个平台包括前台和后台两个部分。

- 前台功能包括：首页、商品详情页、订单、用户中心模块。
- 后台功能包括：总览、订单管理、商品管理、分类管理、标签管理、评论管理、用户管理、运营管理、日志管理、系统信息模块。


后台管理帐号：

用户名：admin123
密码：admin123

### 代码结构

- server目录是后端代码
- web目录是前端代码

### 部署运行

#### 后端运行步骤

(1) 首先下载配置好jdk（我是jdk17）下载代码后，使用IntelliJ IDEA打开server目录

(2) 配置application.yml文件，配置数据库和upload根目录

(3) 安装mysql 8.0数据库，并创建数据库，命名为java_shop，创建SQL如下：
```
CREATE DATABASE IF NOT EXISTS java_shop DEFAULT CHARSET utf8 COLLATE utf8_general_ci
```
(4) 恢复sql数据。在mysql下依次执行如下命令：

```
mysql> use java_shop;
mysql> source D:/xxx/xxx/shop.sql;
```

(5) 启动后端服务：点击IDEA顶部run按钮


#### 前端运行步骤

(1) 安装node 16.14

(2) cmd进入web目录下，安装依赖，执行:
```
npm install 
```
(3) 运行项目
```
npm run dev
```


### 界面预览

首页




后台页面




