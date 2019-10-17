# 循环结构

## 循环结构的应用场景 

 在Python中构造循环结构有两种做法，一种是`for-in`循环，一种是`while`循环。 

### 条件 

当满足条件时，循环执行语句，不满足时，跳出循环。

### 流程图

<img src="D:\MD\100-days-python\Pic\while_loop_1.png" style="zoom:100%;" />

## while循环

### 基本结构 

```python
while 判断条件：
    语句
else:
    语句
```



### break 语句 

 break 语句用于跳出整个循环。



### continue 语句

 continue 语句跳出本次循环 ，让循环进入下一轮。



### pass 语句

 pass 语句是空语句， 不做任何事情，一般用做占位语句，是为了保持程序结构的完整性。 



## for循环 

### 基本结构

```python
for <variable> in <sequence>:
    <statements>
else:
    <statements>
```



### range类型

range() 函数可创建一个整数列表，一般用在 for 循环中。 

```python
range(start, stop[, step])
```

- start: 计数从 start 开始。默认是从 0 开始。例如range（5）等价于range（0， 5）;
- stop: 计数到 stop 结束，但不包括 stop。例如：range（0， 5） 是[0, 1, 2, 3, 4]没有5
- step：步长，默认为1。例如：range（0， 5） 等价于 range(0, 5, 1)



 ### 循环中的分支结构

```python
for <variable> in <sequence>:
	if 判断条件：
		<statements>
```



 ### 嵌套的循环

```python
for <variable> in <sequence>:
    for <variable> in <sequence>:
		<statements>
```



 ### 提前结束程序

无限循环可以使用 CTRL+C 来中断循环。 



## 应用案例

 ### 1~100求和 

### 判断素数 

### 猜数字游戏 

### 打印九九表

### 打印三角形图案

 ### 猴子吃桃 

### 百钱百鸡