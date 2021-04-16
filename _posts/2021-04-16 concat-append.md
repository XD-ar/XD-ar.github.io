---
layout: post
title: "concat()和append()的区别"
subtitle: 'JAVA笔记'
author: "AR"
header-style: text
tags:
  - JAVA
---

**concat()方法：**  String类的concat()方法（只能用于拼接字符串，不能拼接其他类型的数据）将指定的字符串拼接到该字符串的末尾。并且字符串本身和拼接的字符串都不能为null，否则运行程序后会报空指针异常NullPointerException（编译时没有报错）。

**"+"：** 可以对字符，数字，字符串等数据类型的拼接

**append()方法：** 可以对字符，数字，字符串等数据类型的拼接，结果返回一个StringBuffer类型的对象



