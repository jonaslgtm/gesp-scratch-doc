# 2023 年 GESP 图形化编程 2 级认证真题

> 更新完毕.

## 03-1 : 快乐的时光

> CCF GESP 2023年3月认证 图形化编程 2级试题

![03-1 : 快乐的时光](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.03-1-1.jpg)

**准备工作：**

角色：默认小猫角色，添加角色Monkey。

背景：添加背景Forest。

**功能实现：**

（1）小猫与小猴的初始位置如图所示，小猫（X=-100，Y=-90），小猴（X=100，Y = 90）；

（2）小猫和小猴一起跳跃若干次（跳跃的次数为5至10的随机数），每次跳起的高度为50，然后回到原位；

（3）小猫和小猴停止跳跃后，小猫说“一起玩儿真高兴”。

**评分标准：**

（1）小猫与小猴的初始位置为小猫（X=-100，Y=-90），小猴（X=100，Y=90）；（5分）

（2） 利用广播并等待的方式向小猫和小猴发送跳跃的消息；（5分）

（3） 小猫和小猴一起跳跃若干次（跳跃的次数为5至10的随机数），每次跳起的高度为50，然后回到原位；（10分）

（4） 小猫和小猴停止跳跃后，小猫说“一起玩儿真高兴”；（5分）

---

## 03-2 : 绘制图形

> CCF GESP 2023年3月认证 图形化编程 2级试题

![03-2 : 绘制图形](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.03-2-1.jpg)

**准备工作：**

(1) 隐藏默认角色小猫。

**功能实现：**

（1）小猫的初始位置为（x=0,y=0），如上图所示；

（2）设置画笔粗细为3，颜色为红色；

（3）通过次数循环画出所示图形，每条线段的长度为80；

**评分标准：**

（1）小猫的初始位置为（x=0,y=0），面向90度方向； （5分）

（2）设置画笔粗细为3，颜色为红色；（5分）

（3）通过次数循环画出所示图形，每条线段的长度为80；（15分）

---

## 06-1 : 时间规划

> CCF GESP 2023年6月认证 图形化编程 2级试题

![06-1 : 时间规划](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.06-1-1.jpg)

![06-1 : 时间规划](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.06-1-2.jpg)

【**题目描述**】

默认小猫角色和白色背景。

小明在为自己规划学习时间。现在他想知道两个时刻之间有多少分钟。你能通过编程帮他做到吗？

【**输入描述**】

新建变量“h1”，“m1”，用于记录开始时刻，h1表示小时，m1表示分钟。

新建变量“h2”，“m2”，用于记录结束时刻，h2表示小时，m2表示分钟。

注意：时刻使用24小时制，开始时刻和结束时刻是同一天，开始时刻一定在结束时刻之前。

例如：

h1 = 09，m1 = 05，表示开始时刻为09时05分。

h2 = 09，m2 = 06，表示终止时刻为09时06分。

如下图所示：

![06-1 : 时间规划](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.06-1-3.jpg)

【**输出描述**】

新建变量“result”，用于存储得到的结果，即两个时刻之间有多少分钟。

上面的例子09时05分到09时06分，之间有1分钟，所以 result = 1。

如下图所示：

![06-1 : 时间规划](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.06-1-4.jpg)

【**输入样例**】

h1 = 09

m1 = 05

h2 = 09

m2 = 06

【**输出样例**】

result = 1

【**输入样例**】

h1 = 09

m1 = 05

h2 = 10

m2 = 00

【**输出样例**】

result = 55

【**评分标准**】

一共5组测试用例，通过一组测试用例得5分。

测试用例1：

h1 = 09；m1 = 05；h2 = 10；m2 = 04

result = 59

测试用例2：

h1 = 09；m1 = 05；h2 = 09；m2 = 10

result = 5

测试用例3：

h1 = 09；m1 = 55；h2 = 10；m2 = 10

result = 15

测试用例4：

h1 = 09；m1 = 55；h2 = 09；m2 = 59

result = 4

测试用例5：

h1 = 22；m1 = 37；h2 = 23；m2 = 03

result = 26

---

## 06-2 : 统计个数

> CCF GESP 2023年6月认证 图形化编程 2级试题

![06-2 : 统计个数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2024.06-2-1.jpg)

![06-2 : 统计个数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2024.06-2-2.jpg)

【**题目描述**】

默认小猫角色和白色背景。

统计从正整数a到b（包括a和b）之间，能够同时整除c和d的正整数个数。

例如：a = 7，b = 20，c = 2，d = 3，7到20之间能够同时整除2和3的数为12、18一共2个。

【**输入描述**】

新建变量“a”和“b”，用于存储统计个数的区间左右端点。

新建变量“c”和“d”，存储用于整除的数。

如下图所示：

![06-2 : 统计个数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2024.06-2-3.jpg)

【**输出描述**】

新建变量“result”，用于存储得到的结果，表示从a到b（包括a和b）之间所有能够同时整除c和d的正整数个数。

如下图所示：

![03-2 : 找因数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2024.03-2-4.jpg)

【**输入样例**】

a = 7

b = 20

c = 2

d = 3

【**输出样例**】

result = 2

【**输入样例**】

a = 10

b = 30

c = 3

d = 4

【**输出样例**】

result = 2

【**评分标准**】

一共5组测试用例，通过一组测试用例得5分。

测试用例1：

a = 10，b = 100，c = 2，d = 5；

result = 10

测试用例2：

a = 20，b = 200，c = 3，d = 7；

result = 9

测试用例3：

a = 10，b = 100，c = 2，d = 7；

result = 7

测试用例4：

a = 10，b = 100，c = 3，d = 5；

result = 6

测试用例5：

a = 30，b = 300，c = 5，d = 7；

result = 8

---

## 09-1 : 计算标准身高和体重

> CCF GESP 2023年9月认证 图形化编程 2级试题

![09-1 : 计算标准身高和体重](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-1-1.jpg)

![09-1 : 计算标准身高和体重](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-1-2.jpg)

【**题目描述**】

随着生活水平的提高，青少年肥胖率也有上升的趋势。

默认小猫角色和白色背景，给定一个儿童的年龄（age），依据标准身高（height）和体重（weight）的计算公式了解该儿童是否符合标准。

儿童的标准身高（height）= 年龄（age）× 5 + 75（厘米）

儿童的标准体重（weight）= 年龄（age）× 2 + 8（公斤）

例如：age = 2时，height = 2 × 5 + 75 = 85（厘米），weight = 2 × 2 + 8 = 12（公斤）。

【**输入描述**】

新建变量“age”用于存储儿童的年龄（2 ≤ age ≤ 12）。

如下图所示：

![09-1 : 计算标准身高和体重](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-1-3.png)

【**输出描述**】

新建变量“height”，用于存储儿童的标准身高。

新建变量“weight”，用于存储儿童的标准体重。

如下图所示：

![09-1 : 计算标准身高和体重](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-1-4.png)

【**输入样例**】

age = 2

【**输出样例**】

height = 85

weight = 12

【**输入样例**】

age = 12

【**输出样例**】

height = 135

weight = 32

**注意事项：**

1. **<font color="red"> 变量名的拼写（包括大小写）要和题目完全一致。</font>**

2. **<font color="red"> 输入变量直接赋值即可，无需使用“询问并等待”积木块。</font>**

3. **<font color="red"> 输出结果存放在对应变量中即可，无需使用“说...”或“说...，2 秒”积木块。</font>**

---

## 09-2 : 幸运数

> CCF GESP 2023年9月认证 图形化编程 2级试题

![09-2 : 幸运数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-2-1.png)

![09-2 : 幸运数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-2-2.png)

【**题目描述**】

小明很喜欢数字7。所有个位数为7的正整数，以及所有7的倍数，都被小明称为“幸运数”。

默认小猫角色和白色背景，编写程序帮助小明找到正整数 L 和 R 之间（包括 L 和 R，且 1 ≤ L ≤ R ≤ 1000）所有幸运数的和。

例如：L = 10，R = 20，幸运数有 2 个：14 和 17。14 是 7 的倍数，17 的个位数为 7，因此所有幸运数的和为 31。

【**输入描述**】

新建变量“L”用于存储第一个正整数。

新建变量“R”用于存储第二个正整数。

约定 1 ≤ L ≤ R ≤ 1000。

如下图所示：

![09-2 : 幸运数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-2-3.png)

【**输出描述**】

新建变量“result”，用于存储满足条件幸运数的和。

如下图所示：

![09-2 : 幸运数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.09-2-4.png)

【**输入样例**】

L = 10

R = 20

【**输出样例**】

result = 31

【**输入样例**】

L = 1

R = 10

【**输出样例**】

result = 7

【**样例解释**】

1 和 10 之间共有 1 个幸运数：7。因为 7 既是 7 的倍数，个位数又为 7。因此，结果为7。

**注意事项：**

1. **<font color="red"> 变量名的拼写（包括大小写）要和题目完全一致。</font>**

2. **<font color="red"> 输入变量直接赋值即可，无需使用“询问并等待”积木块。</font>**

3. **<font color="red"> 输出结果存放在对应变量中即可，无需使用“说...”或“说...，2 秒”积木块。</font>**

---

## 12-1 : 足球联赛积分

> CCF GESP 2023年9月认证 图形化编程 2级试题

![12-1 : 足球联赛积分](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-1-1.jpg)

![12-1 : 足球联赛积分](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-1-2.jpg)

【**题目描述**】

默认小猫角色和白色背景。

在足球联赛里，一个球队赢下一场比赛得到3个积分，打平一场比赛得到1个积分，输掉比赛得到0分。

现已知一个球队在整个联赛里的比赛情况，求该球队最终的积分。

【**输入描述**】

新建变量“x”，“y”，“z”分别表示这个球队赢下的比赛场数，打平的比赛场数，输掉的比赛场数。（0 ≤ x,y,z ≤ 40）。

如下图所示：

![12-1 : 足球联赛积分](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-1-3.jpg)

【**输出描述**】

新建变量“result”，一个整数，表示该球队最终的积分。

如下图所示：

![12-1 : 足球联赛积分](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-1-4.jpg)

【**输入样例**】

x = 19

y = 6

z = 4

【**输出样例**】

result = 63

【**输入样例**】

x = 3

y = 26

z = 20

【**输出样例**】

result = 35

**注意事项：**

1. **<font color="red"> 变量名的拼写（包括大小写）要和题目完全一致。</font>**

2. **<font color="red"> 输入变量直接赋值即可，无需使用“询问并等待”积木块。</font>**

3. **<font color="red"> 输出结果存放在对应变量中即可，无需使用“说...”或“说...，2 秒”积木块。</font>**

---

## 12-2 : 小杨报数

> CCF GESP 2023年9月认证 图形化编程 2级试题

![12-2 : 小杨报数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-2-1.jpg)

![12-2 : 小杨报数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-2-2.jpg)

【**题目描述**】

小杨需要从 1 到 N 报数。在报数过程中，小杨希望跳过 M 的倍数。例如，如果 N=5，M=2，那么小杨就需要依次报出 1，3，5。

默认小猫角色和白色背景，编写程序计算小杨报数的和（1+3+5=9）。

【**输入描述**】

新建变量“N”（1 ≤ N ≤ 500）。

新建变量“M”（2 ≤ M ≤ 50）。

如下图所示：

![12-2 : 小杨报数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-2-3.jpg)

【**输出描述**】

新建变量“result”，用于存储报数的和。

如下图所示：

![12-2 : 小杨报数](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/2/scratch-2023.12-2-4.jpg)

【**输入样例**】

N = 5

M = 2

【**输出样例**】

result = 9

【**输入样例**】

N = 5

M = 20

【**输出样例**】

result = 15

**注意事项：**

1. **<font color="red"> 变量名的拼写（包括大小写）要和题目完全一致。</font>**

2. **<font color="red"> 输入变量直接赋值即可，无需使用“询问并等待”积木块。</font>**

3. **<font color="red"> 输出结果存放在对应变量中即可，无需使用“说...”或“说...，2 秒”积木块。</font>**