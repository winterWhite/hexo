---
title: Software Architectural Pattern
tags: 
    - BackEnd
---

## Layered pattern 分层模式

基础分层：
1. Presentation layer (UI layer) 表现层
2. Application layer (Service layer) 应用层
3. Business logic layer (Domain layer) 业务层
4. Data access layer (Persistence layer) 数据层

应用场景：
1. General desktop applications 桌面应用程序
2. E commerce web applications 电子商务 Web 应用

示意图：

![Layered pattern](/imgs/architectural-pattern-layered.png)


## Client-server pattern 客户端／服务器模式

服务器监听客户端的所有请求，并进行响应

应用场景：
1. Online applications 线上应用，如 email、banking

示意图：

![Client-server pattern](/imgs/architectural-pattern-c-s.png)


## Master-slave pattern 主从模式

Master 分发工作到 Slaves 的工作模式

应用场景：
1. Database replication 数据库复制中的主数据库和从属数据库
2. Master and Slave drives 主／从驱动器

示意图：

![Master-slave pattern](/imgs/architectural-pattern-m-s.png)


## Pipe-filter pattern 管道过滤器模式

数据 filtering 模式

应用场景：
1. Compilers 编译器
2. Workflows in bioinformatics 生物信息学工作流程

示意图：

![Pipe-filter pattern](/imgs/architectural-pattern-p-f.png)


## Broker pattern 经纪人模式

分布式系统，服务端-代理-客户端模式

应用场景：
1. Message broker software 消息代理软件，如 Apache Kafka

示意图：

![Broker pattern](/imgs/architectural-pattern-broker.png)


## Peer-to-peer pattern 点对点模式

对等体，同时具有服务端／客户端的角色功能，可动态切换

应用场景：
1. File-sharing networks 文件共享网络，如 G2
2. Multimedia protocols 多媒体协议，如 P2PTV

示意图：

![Peer-to-peer pattern](/imgs/architectural-pattern-p2p.png)


## Event-bus pattern 事件总线模式

事件的4个组成部分：Event Source 事件源、Event Listener 事件监听器、Channel 通道、Event Bus 事件总线

应用场景：
1. Android development 安卓开发
2. Notification services 通知服务

示意图：

![Event-bus pattern](/imgs/architectural-pattern-e-b.png)


## Model-view-controller pattern 模型-视图-控制器模式 (MVC)

3个组成部分：
1. Model: Core functionality and data
2. View: Displays the information to the user
3. Controller: Handles the input from the user

解耦数据与用户展示

应用场景：
1. World Wide Web applications 万维网应用架构
2. Web frameworks Web 框架，如 Rails

示意图：

![Model-view-controller pattern](/imgs/architectural-pattern-mvc.png)


## Blackboard pattern 黑板模式

3个组成部分：
1. blackboard 
2. knowledge source
3. control component

应用场景：
1. Speech recognition 语音识别
2. Vehicle identification and tracking 车辆识别与跟踪
3. Protein structure identification 蛋白质结构鉴定
4. Sonar signals interpretation 声纳信号解释

示意图：

![Blackboard pattern](/imgs/architectural-pattern-blackboard.png)


## Interpreter pattern 口译员模式

为语言的每个符号设定一个类，解释专用语言编写的程序组件

应用场景：
1. Database query languages 数据库语言，如 SQL
2. Languages used to describe communication protocols 描述通信协议的语言

示意图：

![Interpreter pattern](/imgs/architectural-pattern-Interpreter.png)


## Compare 对比

![Compare architectural pattern](/imgs/architectural-pattern-compare.png)

