# 培训任务

## 1. 学习任务

### 1.4 Python Web

#### 1.4.1 参考教程

[Flask文档-英文](https://flask.palletsprojects.com/en/2.0.x/) | [Flask文档-中文](https://dormousehole.readthedocs.io/en/latest/quickstart.html)  
[Django文档-3.2](https://docs.djangoproject.com/zh-hans/3.2/)

#### 1.4.2 学习目标

掌握`Flask`、`Django`工程的创建、运行流程，能够自定义`APP`、`URL`、`port`等，比较两者优劣

### 1.5 Java Web

### 1.5.1 参考教程

[SpringBoot](http://c.biancheng.net/spring_boot/)  
[SpringCloud](https://www.fangzhipeng.com/spring-cloud.html)  
[Dubbo官方文档入门](https://www.jianshu.com/p/c9d30c8f856f)  
Mysql：

### 2.学习目标

掌握以下 `Spring Cloud` 常用组件的使用方法与应用场景：`Eureka`、`Ribbon`、`Feign`、`Hystrix`、`Zuul`、`Config`。每个组件的详细教程，在学习资料里都有介绍

## 2. 工程任务

### 2.1 创建Git仓库

### 2.2 Flask

1. 用户输入文本，创建 `hanlp` 自带分词，命名实体识别等(尽可能多的实现)

### 2.3 Django

1. 提供`get`请求：用户输入文本，使用`jieba`统计出文本词频并排序，返回其`json`结果；
2. 提供`post`请求：用户上传`json`文件，格式为`title`、`content`； 使用正则表达式对`title`进行问句分析，判断`title`是否为问句，并进行标识； 
尽可能使用正则表达式提取`content`中时间、地点、人物，标记英文、数字，连同`title`、`content`
存入`mysql`和`es`中；
3. 提供`post`请求：根据用户问题提供查询`es`数据接口；
4. 前端展示：设计页面展示问答；

## 2.4 TensorFlow Serving

1. 根据提供的阅读理解`serving`版本模型以及`Python`版本预测代码，部署阅读理解模型(`cpu`版即可，有机器和能力的尝试部署`gpu`版本)；

## 2.5 SpringBoot+MyBatis

1. 提供用户登录注册+配套页面；
2. 提供接口调用`hanlp`功能； 
3. 提供接口调用`tensorflowServing`（需转写`Python`代码为`Java`代码）； 
4. 提供查询`es`数据接口；

### 2.6 Docker

1. 部署flask、django和springboot+mybatis项目；