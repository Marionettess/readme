# 概述
## 编写目的
本文档包含实训流程标准化XX项目的功能
## 文档团队
*XXX项目团队*
# 项目前景与范围
## 项目前景
## 项目范围
**客户端：**  
用户注册；  
用户登录；  
查询；  
个人信息管理；  
**服务器：**  
增删改查；  
推荐管理；  
用户管理；  
**超出范围：**  
    无。  
# 需求描述
## 角色分析
![MD](https://imgsa.baidu.com/baike/c0%3Dbaike180%2C5%2C5%2C180%2C60/sign=d997317c11ce36d3b6098b625b9a51e2/00e93901213fb80ef9ceac7132d12f2eb938947d.jpg)


# 功能性需求
1. 用户输入账号和密码
2. 用户点击登录按钮
3. 系统验证账号和密码
4. 登录页转跳至首页

- 用户输入账号和密码
- 用户点击登录按钮
+ 系统验证账号和密码
+ 登录页转跳至首页

<http://www.baidu.com>  
[百度首页](http://www.baidu.com)

版本|修改内容|修改时间
---|---|---
v0.1|需求描述|2016-01-01|

- [x] 需求分析
- [ ] 编码开发
- [ ] 系统测试

```html
<body>
<div id="title">
<h1>Markdown标记语言</h1>
<img src="./imgs/logo.jpg" class="pic" />
</div>
</body>
```
    <body>
    <div id="title">
    <h1>Markdown标记语言</h1>
    <img src="./imgs/logo.jpg" class="pic" />
    </div>
    </body>
    
> 引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字
>>引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字引用文字


```
graph TD
ST[开始]-->A
A[用户管理]-->B{是否注册}
B-->|是|B1(输入用户名密码)
B-->|否|B2(注册)
B1-->C[登录]
C-->D[完善个人信息]
B2-->E[注册完成]
E-->B
D-->END[结束]
```

```
gantt
title 产品计划表
dateFormat YYYY-MM-DD
section 前期
需求分析:2016-11-11, 8d
section 中期
编码开发:2016-11-11, 15d
section 后期
系统测试:2016-11-26, 15d
``` 
