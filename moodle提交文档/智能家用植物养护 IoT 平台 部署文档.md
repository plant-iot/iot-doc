# 智能家用植物养护 IoT 平台 部署文档

## 目录

[TOC]

** **

## 更新历史

| 修改人员         | 日期        | 变更原因 | 版本号  |
| ------------ | --------- | ---- | ---- |
| 许杨 | 2021.4.14 | 创建文档 | V1.0 |

## 一、引言

本文档以图文形式，具体说明项目的部署工作。

## 二、部署环境

1.      系统配置：全平台适用  
2.      系统依赖配置：系统需要安装 JDK
3.      数据库系统：智能家用植物养护 IoT 平台采用的是MySQL 5.7.30版本，请使用root用户建立名为iot_platform的数据库（项目运行的数据库地址为**mysql://localhost:3306/iot_platform**，创建数据库的命令为```create database iot_platform```）

## 三、项目配置

1. 请先从github下载项目源码

   1. 后端代码仓：<https://github.com/plant-iot/iot-backend.git>
   2. 前端代码仓：<https://github.com/plant-iot/iot-frontend.git>

2. 后端配置

   1. 修改iot-backend\src\main\resources\application.properties文件

      1. 修改第9~10行mysql用户名、密码

         ![](pic\部署文档\mysql_config.png)

      2. 修改第32~38行MQTT配置

         ![](pic\部署文档\mysql_config.png)

## 四、运行项目

1. 启动后端项目
   1. 启动后端IotApplication.java
2. 启动前端项目

