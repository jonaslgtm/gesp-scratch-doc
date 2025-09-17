# GESP 图形化编程 3 级认证样题

> 更新完毕 .

## 样题01 : 鸡兔同笼

> GESP 图形化编程 3 级认证样题

【**题目描述**】

在小明家的院子里养了一群鸡和兔子，鸡有两只脚，兔子有四只脚，兔子和鸡都只有一个头。

目前已知所有鸡和兔子头的数量为 head，脚的数量为foot。

默认小猫角色和白色背景，编写程序计算鸡（chicken）和兔子（rabbit）的数量。

【**输入描述**】

新建变量“head”用于存储鸡和兔子头的总数量，新建变量“foot”用于存储鸡和兔子脚的总数量。

如下图所示：

![样题01 : 鸡兔同笼](https://cdn.jsdelivr.net/gh/jonaslgtm/gesp-scratch-doc/docs/_img/scratch-sample-3-01.jpg)

【**输出描述**】

新建变量“chicken”用于存储鸡的数量，新建变量“rabbit”用于存储兔子的数量。

如下图所示：

![样题01 : 鸡兔同笼](https://cdn.jsdelivr.net/gh/jonaslgtm/gesp-scratch-doc/docs/_img/scratch-sample-3-02.jpg)

【**输入样例**】

head = 20

foot = 50

【**输出样例**】

chicken = 15

rabbit = 5

【**输入样例**】

head = 35

rabbit = 100

【**输出样例**】

chicken = 20

rabbit = 15

---

## 样题02 : 数字加密

> GESP 图形化编程 3 级认证样题

【**题目描述**】

在信息科技的课堂上，科技老师提了一个问题“如何对十进制的四位数进行加密呢？” 小明想到的方法是：首先，将个位和千位对调，再将十位和百位对调；然后，将每位数字按照一定规则进行替换。

替换规则为：0 替换成 9、1 替换成8、2 替换成7、其他数字以此类推，直到 9 替换成 0。

例如，对 1978（称之为明文） 加密，则：

个位和千位对调后得 8971;

十位和百位对调后得 8791;

将每个数字替换后得 1208（称之为密文）。

默认小猫角色和白色背景，现给定一个密文的四位数，请编写程序，解码得出明文的四位数。

【**输入描述**】

新建变量“密文”，存入一个四位数，且保证输入的密文有且仅有四个数字。

如下图所示：

![样题02 : 数字加密](https://cdn.jsdelivr.net/gh/jonaslgtm/gesp-scratch-doc/docs/_img/scratch-sample-3-03.jpg)

【**输出描述**】

新建变量“result”，将最后的结果存入变量“result”，表示对应的明文。

如下图所示：

![样题02 : 数字加密](https://cdn.jsdelivr.net/gh/jonaslgtm/gesp-scratch-doc/docs/_img/scratch-sample-3-04.jpg)

【**输入样例**】

密文 = 1978

【**输出样例**】

result = 1208

【**输入样例**】

密文 = 0557

【**输出样例**】

result = 2449
