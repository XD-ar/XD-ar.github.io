---
layout: post
title: "C++和JAVA遍历字符串的方法"
subtitle: '笔记'
author: "AR"
header-style: text
tags:
  - JAVA
  - cpp
---

### C++

在 C++ 语言中， string 被设计成「可变」的类型。  

```c++
for(int i=0;i < str.size();i++){
    printf("%c",str[i]);
}

//增强for
for(char c:str){
    printf("%c",str[i]);
}
```

### JAVA  

在Java 语言中，字符串被设计成「不可变」的类型，即无法直接修改字符串的某一位字符。  

### 方法一：.length()， charAt()  

```java
for(int i=0;i < str.length();i++){
	System.out.println(str.charAt(i));
}
```

### 方法二：.length()， substring(i ,i+1)  

```java
for(int i=0;i < str.length();i++) {
	 System.out.println(str.substring(i,i+1)); 
}
```

###  方法三：.toCharArray()  

```java
//完整写法
char[]  c = str.toCharArray(); 
for(int i=0;i < c.length;i++) {   
	System.out.println(c[i]);
}

//省略写法
for(Character c:str.toCharArray()){
    System.out.println(c);
}
```

