## 04-print()函数

<hr/>

### 一：print()函数可以输出哪些内容？

1. 数字
2. 字符串
3. 条件表达式

**演示：**

```python
print(520)
print('hello word')
print("hello word")
print(5+1)
```

**输出：**

```python
520
hello word
hello word
6
```

<mark>注意：python中，双引号与单引号没有区别</mark>



### 二：print()函数可以将内容输出的目的地

1. 显示器
2. 文件

**演示：**

```python
# 将数据输出到文件中
fp = open('./print函数.txt','a+')	# 类似php中的打开文件
print('hello！！！',file=fp)
fp.close() # 关闭文件
```

**打开同级文件 *print函数.txt***

```python
hello！！！
```

<mark>注意：如果不存在指定的文件会自动创建一个，如果存在会在文件内容后追加内容</mark>



### 三：拓展

1. print()不换行输出

**演示：**

``` python
# 不换行输出
print('hello','nb','ter')
```

**输出：**

``` python
hello nb ter
```

