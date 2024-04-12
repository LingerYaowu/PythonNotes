## 10-input()的使用

<hr/>

### 1. input( )基本使用

+ 作用：用于接收用户的输入，并返回一个 str 类型的值，可以使用赋值运算符赋给变量

+ name<sup><mark>1</mark></sup>  =<sup><mark>2</mark></sup>  input()<sup><mark>3</mark></sup>

  <sup><mark>1</mark></sup>：变量

  <sup><mark>2</mark></sup>：赋值运算符，将右边接收到的值作为 str 赋给左边的变量

  <sup><mark>3</mark></sup>：input( )函数是一个输入函数，参数用作给用户的提示信息

+ **演示：**

  ```python
  name = input("请输入你的名字：")
  print("你的名字是 "+name)
  print("name的类型：",type(name))
  ```

  **输出：**

  ```python
  请输入你的名字：桂桂
  你的名字是 桂桂
  name的类型： <class 'str'>
  ```

  

### 2. 从键盘输入两个整数，计算两个整数的和

**演示：**

```python
num1 = input("请输入第一个整数：")
num2 = input("请输入第二个整数：")
print("这两个整数的和是："+str(int(num1)+int(num2)))
```

**输出：**

```python
请输入第一个整数：2
请输入第二个整数：6
这两个整数的和是：8
```

<mark>注意</mark>：input( )接收到的值是 str 类型的，要进行算术运算要先转换为 int 型。
