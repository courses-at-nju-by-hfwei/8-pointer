# 内存解释器(interpreter.c)

## 题目描述

输入一个八位十六进制整数`x`，表示内存当中一个 `int` 类型的数据。请将该内容分别解释为

1. 有符号整型
2. 无符号整型
3. 32位浮点型

并分别输出解释之后的数据。

## 输入格式

一行，一个8位16进制整数`x`.

## 输出格式

三行，分别是解释后的十进制有符号整型、十进制无符号整型、32位浮点型（保留6位小数）。

## 脚注

不需要思考小端存储的事（

## 样例

### 样例输入

8000001a

### 样例输出

-2147483622
2147483674
-0.000000

### 样例输入

f7fffff4

### 样例输出

-134217740
4160749556
-10384586289429419544779343263694848.000000
