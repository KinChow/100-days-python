# 初识Python

## Python简介

### Python的历史

略

### Python的优缺点

优点：

1. 简单和明确，做一件事只有一种方法。
2. 学习曲线低，跟其他很多语言相比，Python更容易上手。
3. 开放源代码，拥有强大的社区和生态圈。
4. 解释型语言，天生具有平台可移植性。
5. 对两种主流的编程范式（面向对象编程和函数式编程）都提供了支持。
6. 可扩展性和可嵌入性，例如在Python中可以调用C/C++代码。
7. 代码规范程度高，可读性强，适合有代码洁癖和强迫症的人群。

缺点：

1. 执行效率稍低，因此计算密集型任务可以由C/C++编写。
2. 代码无法加密，但是现在很多公司都不销售卖软件而是销售服务，这个问题会被弱化。
3. 在开发时可以选择的框架太多（如Web框架就有100多个），有选择的地方就有错误。

### Python的应用领域

Web应用开发、云基础设施、DevOps、网络数据采集（爬虫）、数据分析挖掘、机器学习等。

## 搭建编程环境

### Windows环境

略

### Linux环境

略

### MacOS环境

略

## 从终端运行Python程序

### 确认Python的版本

#### Windows的命令行提示符

```bash
python --version
```

#### 在Linux或macOS系统的终端

```bash
python3 --version
```

#### 交互式环境

```python
import sys

print(sys.version_info)
print(sys.version)
```



### print函数

```python
print('hello, world!')
```



### 运行程序

切换到源代码所在的目录，打开命令行提示符或终端并执行下面的命令。

```bash
python hello.py
```

或

```bash
python3 hello.py
```



## 使用IDLE

### 交互式环境(REPL) 

#### IDLE - 自带的集成开发工具

#### IPython - 更好的交互式编程工具

#### Sublime Text - 高级文本编辑器

#### PyCharm - Python开发神器

### 编写多行代码

使用`'''`编写多行代码。

### 运行程序

### 退出IDLE

## 注释

### 注释的作用

注释是编程语言的一个重要组成部分，用于在源代码中解释代码的作用从而增强程序的可读性和可维护性，当然也可以将源代码中不需要参与运行的代码段通过注释来去掉，这一点在调试程序的时候经常用到。注释在随源代码进入预处理器或编译时会被移除，不会在目标代码中保留也不会影响程序的执行结果。

### 单行注释

以#和空格开头的部分

### 多行注释

三个引号开头，三个引号结尾



## 练习

1. 在Python交互式环境中输入下面的代码并查看结果，请尝试将看到的内容翻译成中文。

```python
import this
```

输出python之禅。

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!

2. 学习使用turtle在屏幕上绘制图形。