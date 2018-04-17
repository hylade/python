# python

## 暂停一秒输出

需要使用time的sleep函数，如：

```python
import time
m = [1, 2, 3, 4]
for i in m:
	print(i)
	time.sleep(1）
```



## time strftime（）

Python time strftime() 函数接收以时间元组，并返回以可读字符串表示的当地时间，格式由参数format决定

语法：

```python
time.strftime(format[,t])
```

- format -- 格式字符串
- t -- 可选的参数t是一个struct_time对象

如获取本地时间代码：

```python
import time
print(time.strftime('%Y-%m-%d %H:%M:%S',time.localtime(time.time())))
time.sleep(1)
print(time.strftime('%Y-%m-%d %H:%M:%S',time.localtime(time.time())))
```



## ord（）函数

能以一个字符（长度为1的字符串）作为参数，返回ASCII码或者Unicode数值



## chr（）函数

作为ord（）的配对函数，以一个整数作为其参数，返回相应的字符



## python输出自动换行

1.可以使用```print(x, end="")```的方法

2.可以导入sys模块，如```sys.stdout.write()```



## 绘制多个图形

```matplotlib.pyplot```默认有一个```figure```（窗口），可以通过```plt.figure()```生成多个窗口，以便于对比等

