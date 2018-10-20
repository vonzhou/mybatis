# MyBatis 源码阅读


## 日志 logging

org.apache.ibatis.logging

代理模式

## 绑定 binding

org.apache.ibatis.binding

## 缓存 Cache

org.apache.ibatis.cache

门面模式 

应用在一级,二级缓存中,具体见 Executor 模块

## Executor  执行器模块

模板方法模式,装饰器模式

## Plugin 插件

责任链模式,代理模式

PageHelper就是利用了mybatis的插件功能实现的


## Parsing 解析

xml解析，${} 格式的字符串解析

## TypeHandler 类型处理器

实现java和jdbc中的类型之间转换

## IO

通过类加载器在jar包中寻找一个package下满足条件(比如某个接口的子类)的所有类

## 反射

## 数据源

## 事务


## 会话

接口层

## JDBC

## Builder 构建

## Mapping 映射

## Scripting 脚本


SqlNode

Mapper XML 中动态语言的解析



## TODO 

根据测试用例再看代码

梳理里面使用到的设计模式


学习JDBC编程

mybatis-spring解决了哪些问题
