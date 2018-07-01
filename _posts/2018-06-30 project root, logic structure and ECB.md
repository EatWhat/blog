---
layout: post
title: About
description: 项目目录逻辑结构
category: blog
---
# 1. 项目目录
![project](https://github.com/EatWhat/EatWhat.github.io/blob/master/img/project%20directory.png)

# 2. 目录解释

## 2.1 前端

1. code: 存放前端小程序项目代码
	- img: 存放各类图片
	- pages: 存放各种页面，有菜单、购物车等页面。**ECB中的各种page**
	- utils: 存放功能性代码
	- app.js: 用于启动项目
	
2. 接口文档: 存放前后端交互的接口文档

## 2.2 后端
1. sql: 定义数据库各个字段。也就是**ECB中的Entities**
2. src: 各类控制代码
	- handler: 控制层，操作数据库并向上传递数据。**ECB中的Controller**
		- get_name.py
		- login.py
		- ...
	- mysql.py 各类底层的数据库操作
	- settings.py 数据库连接用的设置
	- urls.py: 定义了路由处理逻辑
3. app.py: 启动项目
