---
layout: post
title: About
description: 项目规划
category: blog
---
## 关于 EatWhat
EatWhat（食咩阿）是一款支持扫码点餐、外卖、预约位置的小程序

主要功能有：
* 用户到店扫描二维码进入该商家页面点餐
* 用户通过小程序点外卖
* 用户通过小程序进行餐厅位置预约

## Documentation
# Dashboard
Record the whole development process of **EatWhat**.
# Core Artifacts
- 1、[About(项目规划)](https://eatwhat.github.io/)
- 2、[Team profile(团队组建)](https://github.com/EatWhat/EatWhat.github.io/blob/master/_posts/2018-04-15-Team%20Profile.md)
- 3、[Investigation(项目前期调研)](https://github.com/EatWhat/documents/blob/master/%E8%B0%83%E7%A0%94%E6%8A%A5%E5%91%8A.md)
- 4、Vision(项目愿景)
- 5、[Product Backlog(产品特性)](https://github.com/EatWhat/EatWhat.github.io/blob/master/_posts/2018-04-15-Vision.md)
- 6、Requirement specification(需求规格说明书)
	- 6.1 [Usecase Diagram (用例图)](https://github.com/EatWhat/EatWhat.github.io/blob/master/_posts/2018-04-14-Usecase%20Diagram.md)
	- 6.2 [Use Cases (用例+活动图)](https://github.com/EatWhat/documents/blob/master/_usecase.png)
	- 6.3 [Domian Model (领域模型)](https://github.com/EatWhat/documents/blob/master/_domain.png)
	- 6.4 [State Model (状态模型)](https://github.com/EatWhat/documents/blob/master/_state.png)
	- 6.5 System Sequence Diagram (功能模型)
		- [订单拒绝以及重新修改场景 - 15331118](https://github.com/EatWhat/documents/blob/master/sequence.png)
		- [订单支付场景 - 15331119](https://github.com/EatWhat/documents/blob/master/_payment_sequence.png)
		- [商家地址定位场景 - 15331101](https://github.com/EatWhat/documents/blob/master/address_search_restaurant_sequence.png)
		- [微信登陆场景 - 15331099](https://github.com/EatWhat/documents/blob/master/%E5%BE%AE%E4%BF%A1%E7%99%BB%E5%BD%95%E9%A1%BA%E5%BA%8F%E5%9B%BE.png)
	        - [订单取消与修改场景]()  
     - 6.6 [Supplementary Requirements（补充需求）](https://github.com/EatWhat/documents/blob/master/%E8%A1%A5%E5%85%85%E6%80%A7%E8%A7%84%E6%A0%BC%E8%AF%B4%E6%98%8E.md)
- 7、Design(设计)
	- 7.1 UI design
		- ["食咩啊"App用例 UI设计](https://github.com/EatWhat/EatWhat.github.io/blob/master/_posts/2018-04-14-UI%20Diagram.md)
	- 7.2 Database design
		- 7.2.1 [用户及权限系统数据库设计](https://github.com/EatWhat/documents/blob/master/database_design/database%20table%20design%20ver0.1.md)
		- 7.2.2 XX子系统数据库设计
		- 7.2.x 第三方数据评审结果
	- 7.3 [API设计](https://github.com/EatWhat/front-end/tree/master/%E6%8E%A5%E5%8F%A3%E6%96%87%E6%A1%A3)
	- 7.4 [Software Architecture Document](https://github.com/EatWhat/documents/blob/master/Software%20Architecture%20Document.md) 
- 8、生产规范与指南
	- 8.1 安卓代码规范
	- 8.2 REST API设计规范
- X1 meeting_recording
	- [meeting_recording(18/04/15)](https://eatwhat.github.io/2018-04-15-meeting_record/)
	- Iteration X meeting(yy/mm/dd)
- X2 Tech/Work Report
        * [EatWhat:微信小程序开发一](http://richbabe.top/2018/04/15/EatWhat_blog(1)/)

## Iterations
### Iterations 1
目标：小程序实现点餐界面、购物车界面、订单界面。用户能够点餐并将该菜式加入购物车，点击提交订单该订单能够成功传到商家。

#### Week 1(2018/04/01 - 2018/04/07)
业务方面：
* 完成团队组建
* 完成项目愿景
* 完成产品特性

技术方面：
* 完成第一次迭代的MVC和UML设计，完成第一次迭代的UI交互设计
* 搭建团队项目Github
* 确定前后端技术框架，前后端的分工与协作

#### Week 2(2018/04/08 - 2018/04/15)
业务方面：
* 完成项目前期调研

技术方面：
* 完成第一次迭代用例图设计
* 完成第一次迭代数据库设计
* 前端：学习小程序框架以及基本用法
* 后端：学习服务器的搭建以及数据库的连接

