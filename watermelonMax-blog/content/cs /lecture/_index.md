---
title: "课堂笔记"
date: 2023-12-07
description: " "
summary: " ."
tags: ["cs"]
showDate: true
type: 'cs'
---

## 

## 课程简介

这门课程是基于 *Structure and Interpretation of Computer Programs (SICP)* 改编的python版本教材，java版本可以参考课程cs61b。

课程官网 <https://cs61a.org/>



## Week 1 



### lecture 1

根据lab00的指示，完成终端、编辑器vs安装，作业提交ok系统

本地提交 ```python ok --local```



### lecture 2 

1. python 计算机程序状态的可视化工具

python tutor：http://pythontutor.com/composingprograms.html#mode=edit

2. Pure Functions & Non-pure functions

   Pure Function : just return values , print return values

   Non-Pure Functions: have side effects. Print the output and None. A sdie effect isn't a value; its anything that happens as a consequence of calling a functions.



### lecture 3

1. 多环境
2. Miscellaneous Python Features
   + Python3 -i ~.py : 交互模式执行python

3. Conditional statements

   ![image-20231208135945674](/Users/max/Library/Application Support/typora-user-images/image-20231208135945674.png)

    

4.  Iteration
   + while statement is a compound statement

### lecture 4

1.  Fibonacci sequence

   ```
   def fib(n):
       pre, curr = 0, 1
       k = 1
       while k < n:
           pre, curr = curr, pre + curr
           k = k + 1
       return curr 
   ```

2. if - else 语句

   ![image-20231208195344895](/Users/max/Library/Application Support/typora-user-images/image-20231208195344895.png)

   if_语句，三个操作必须同时有效才可有

3. Higher order function

   ![image-20231208202543214](/Users/max/Library/Application Support/typora-user-images/image-20231208202543214.png)

![image-20231208202919277](/Users/max/Library/Application Support/typora-user-images/image-20231208202919277.png)

![image-20231208203615078](/Users/max/Library/Application Support/typora-user-images/image-20231208203615078.png)

4. Function as Return Values

   ![image-20231208204557663](/Users/max/Library/Application Support/typora-user-images/image-20231208204557663.png)



## lecture 5

### Environments for Higher-Order Functions

Higher-order function: A function that takes a function as an argument value or returns a function as a return value

![image-20231212185856037](/Users/max/Library/Application Support/typora-user-images/image-20231212185856037.png)



![image-20231212193645897](/Users/max/Library/Application Support/typora-user-images/image-20231212193645897.png)

![image-20231212193413319](/Users/max/Library/Application Support/typora-user-images/image-20231212193413319.png)











