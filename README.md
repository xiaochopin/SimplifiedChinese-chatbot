# SimplifiedChinese-chatbot

[原博地址](https://blog.home-chopin.xyz/2022/08/13/chatbot.html)

## 基于Python的中文聊天bot

#### 简介

基于Python直接调用大厂的API实现的聊天效果,项目已开源→[SimplifiedChinese-chatbot](https://github.com/xiao-chopin/SimplifiedChinese-chatbot),欢迎给我star

#### 项目演示

首先`clone`项目文件.

进入项目文件夹.

```ruby

python chatbot.py //启动项目

start //初始化

你有病啊？ //输入

我有病啊！ //输出

```

#### 代码解析

```ruby

start = input("")

#获取初始化输入

while start == "start":

#判断初始化口令

print(input("").replace("你","我").replace("吗","").replace("？","！")

#获取用户输入并调用API进行输出

```

在最后一行代码中,`input("")`为获取输入用,而后面一长串东西为`老师好我是萧同学文化传媒有限公司`AI聊天bot的API密钥,我搞了一下午才编出来的().

> 太美丽啦北邮,哎呀这不是赛博丁真吗.

给!我!star!啊啊啊啊啊啊啊!

![ecdc2611bd831ffde4d1a0b02bb053ca.jpeg](https://s2.loli.net/2022/08/13/bYXWiam1PZfKec9.jpg)

