# Study
- [数据类型与变量](#1)
- [字符串和编码](2)
- [数据类型与变量](3)

# Python
<a name="1"></a>
## 数据类型与变量

**基本数据类型**
- 整数型：任意大小整数，无short,int,long区分 0x表示16进制
- 浮点型：即小数（科学计数法小数点可浮动）
PS:整数运算永远准确，浮点数运算存在四舍五入
- 字符串：用''或""括起来的内容
PS：转义字符：\。不转义：r'...'。多行内容：'''...'''
- 布尔值：True，False PS：and or not运算
- 空值：None

**变量**
- 起名：下划线、字母、数字组合不能以数字开头 PS：动态语言，变量无类型

**常量**
- 名称通常大写。实际无法约束常量不变

<a name="2"></a>
## 字符串和编码

**字符编码**
- 一个比特位只能表示0或者1
- 8个比特位表示一个字节
- n个字节可以表示一个字符（n视编码方式而定）
- ASCII编码：一个字节，只能表示英文及常用字符
- Unicode编码：常用两个字节表示，通用
- UTF-8编码：变字节长度，英文一个字节，兼容ASCII，中文３个
- 存储和网络传输常用UTF-８，内存中常用Unicode

**字符串**
- ord()函数：取字符整数表示
- chr()函数：取整数字符表示
- b'...'表示比特类型数据
- .encode('utf-8,ascii,unicode')函数，将字符按指定编码方式编码为比特型
- .decode('utf-8,ascii,unicode')函数，将比特按指定编码方式编码为字符

**格式化字符串**
- %d 整数型
- %s 字符串型
- %f 浮点数型
- %x 十六进制整数型
PS：整数和浮点数型可指定是否补0或小数点位数（%02d,%.2f）

<a name="3"></a>
## 数据类型与变量
** 使用list和tuple**
*** list***
- 用len()函数可以获得list元素的个数：

`>>> len()`
- list是一个可变的有序表，所以，可以往list中追加元素到末尾：

`>>> list.append('str')`
- 也可以把元素插入到指定的位置，比如索引号为1的位置：

`>>> list.insert(1, 'str')`
- 要删除list末尾的元素，用pop()方法：

`>>> list.pop()`
- 要删除指定位置的元素，用pop(i)方法，其中i是索引位置：

`>>> classmates.pop(1)`



