# 2023 年 GESP 图形化编程 1 级认证真题

> 更新完毕 .

## 03-1 : 问路

> CCF GESP 2023年3月认证 图形化编程 1级试题

![03-1 - 问路](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.03-1-1.jpg)

![03-1 - 问路](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.03-1-11.jpg)

**准备工作：**

(1) 背景：删除默认白色背景，添加背景 Urban 和 School。

(2) 角色：删除默认小猫角色，添加角色 Avery 和 Dee。

(3) 删除 Avery 的 avery-b 造型，并添加 Avery Walking-a、Avery Walking-b、Avery Walking-c、Avery Walking-d 四个造型。

**功能实现：**

（1）用积木块实现，初始背景为 Urban，Avery 的初始位置为舞台的左下角（X=-163，Y=-73），面向右边，初始造型为 avery-a，Dee 站在 Avery 对面（X=-47，Y=-76），面向左边，如上图所示；

（2）Avery 说“请问红旗小学怎么走？”2 秒，Dee 回答说“一直向前走就到啦” 2 秒；

（3）询问到路的 Avery 径直走向舞台的右侧边缘，边走边切换造型（每次按照 Avery Walking-a、Avery Walking-b、Avery Walking-c、Avery Walking-d 的顺序进行切换，每次切换间隔 0.1 秒，移动 10 步）。

（4）Avery 走到舞台右侧边缘后，背景换为 School，Avery 移到舞台的左下角（X=-163，Y=-73），说“找到红旗小学啦”2 秒。

（5）当背景换为 School 时，Dee 消失。

**注意事项：**

- 本程序只允许使用运动、外观、事件（除广播）、控制、侦测类积木块。

---

## 03-2 : 小猫捉老鼠

> CCF GESP 2023年3月认证 图形化编程 1级试题

![03-1 - 小猫捉老鼠](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.03-1-2.jpg)

**准备工作：**

(1)导入背景 Room 2；

(2)删除默认小猫角色，导入角色 Mouse1、Cat 2。

**功能实现：**

(1)点击绿旗，老鼠出现在随机位置；

(2)通过键盘的“↑”、“↓”、“←”、“→”键来控制小猫行走，每按一次，移动 5 步；

(3)小猫在行走过程中需要面向不同方向；

(4)当小猫碰到老鼠时，老鼠发出 pop 的声音并隐藏起来（被“吃掉”），一秒后老鼠重新出现在随机位置。

**注意事项：**

- 本程序只允许使用运动、外观、事件（除广播）、控制、侦测类积木块。

---

## 06-1 : 去旅行

> CCF GESP 2023年6月认证 图形化编程 1级试题

![06-1 - 去旅行](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.06-1-1.jpg)

**准备工作：**

（1）删除默认小猫角色。

（2）添加角色 Avery Walking,并为其添加声音 Bossa Nova。

（3）删除默认白色背景，添加背景 Beach Malibu、Hay Field、Canyon、Savanna。

**功能实现（用积木块实现下列描述的功能）：**

（1）点击绿旗，角色 Avery Walking 的初始位置为（X=-170，Y=-80），初始造型为 avery walking-a，面向舞台右侧，开始播放音乐 Bossa Nova。舞台的初始背景为 Beach Malibu。

（2）等待 1 秒钟后，Avery Walking 向右移动 80 步，从 avery walking-a 造型切换到 avery walking-b 造型，进入 Hay Field 背景。

（3）进入 Hay Field 背景后，等待 1 秒钟，Avery Walking 向右移动 80 步，从 avery walking-b 造型切换到 avery walking-c 造型，进入 Canyon 背景。

（4）进入 Canyon 背景后，等待 1 秒钟，Avery Walking 向右移动 80 步，从 avery walking-c 造型切换到 avery walking-d 造型，进入 Savanna 背景。

（5）进入 Savanna 背景后，等待 1 秒，停止所有声音。

**注意事项：**

- 所有的积木都必须在 Avery Walking 下，并且只用一个【当开始被点击】积木。

---

## 06-2 : 小猫寻宝

> CCF GESP 2023年6月认证 图形化编程 1级试题

![06-2 - 小猫寻宝](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.06-1-2.jpg)

**准备工作：**

（1）保留默认小猫角色，添加角色 Crystal。

（2）删除默认白色背景，添加背景 Mountain。

**功能实现（用积木块实现下列描述的功能）：**

（1）点击绿旗，小猫角色的初始位置为（X=-170，Y=-120），面向方向为 90°，旋转方式为左右翻转。在小猫角色中设置舞台的初始背景为 Mountain。

（2）点击绿旗，Crystal 角色的初始位置为（X=170，Y=0），初始大小为 120，Crystal 角色每隔 0.5 秒钟颜色特效增加 25。

（3）小猫能够面向鼠标指针，以移动 10 步，等待 0.2 秒的速度在舞台上移动。

（4）在移动过程中，小猫如果找到 Crystal，说“发现宝石”2 秒，停止全部脚本。

---

## 09-1 : 跳舞

> CCF GESP 2023年9月认证 图形化编程 1级试题

![09-1 - 跳舞](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.09-1-1.png)

**准备工作：**

（1）删除默认小猫角色。

（2）添加角色 Ballerina,并为其添加声音 Dance Around。

（3）删除默认白色背景，添加背景 Spotlight。

**功能实现（用积木块实现下列描述的功能）：**

（1）点击绿旗，角色 Ballerina 的初始位置为（X=10，Y=0），初始方向 90°，初始造型为 ballerina-a。

（2）点击绿旗，舞台的初始背景为 Spotlight，清除图形特效，每隔 1 秒颜色特效增加 25，一共增加 10 次。

（3）播放音乐 Dance Around，Ballerina 说“开始跳舞”2 秒后，开始跳舞，每隔 0.5 秒切换一次造型，一共切换 20 次。

（4）跳舞结束，停止播放音乐，Ballerina 说“谢谢大家”，2 秒。

**注意事项：**

- 功能（1）、（3）、（4）全部写在 ballerina 角色代码区的【当绿旗被点击】积木下面。

- 功能（2）全部写在背景代码区的【当绿旗被点击】积木下面。

---

## 09-2 : 小鸡躲球

> CCF GESP 2023年9月认证 图形化编程 1级试题

![09-2 - 小鸡躲球](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.09-1-2.png)

**准备工作：**

（1）删除默认小猫角色。

（2）添加角色 Chick 和 Ball。

（3）删除默认白色背景，添加背景 Blue Sky。

**功能实现（用积木块实现下列描述的功能）：**

（1）点击绿旗，小鸡角色站在地面上，初始位置为（X=-140，Y=-120），初始方向为 90°，旋转方式为任意旋转。在小鸡角色中设置舞台的初始背景为 BlueSky。

（2）点击绿旗，小球角色的初始位置为（X=210，Y=-140），初始大小为 80，面向方向为-90°。

（3）小球从初始位置（舞台右边）水平地滚到舞台左边碰到边缘后，再移到初始位置，一直执行下去。

（4）按下空格键，小鸡向上跳起一段距离后，又落到地面。

（5）小鸡碰到小球，程序终止。

**注意事项：**

- 功能（1）、（5）全部写在 Chick 角色代码区的【当绿旗被点击】积木下面。

- 功能（4）写在 Chick 角色代码区的【当按下空格键】积木下面。

- 功能（2）、（3）全部写在 Ball 角色代码区的【当绿旗被点击】积木下面。

---

## 12-1 : 返回地球

> CCF GESP 2023年12月认证 图形化编程 1级试题

![12-1 - 返回地球](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.12-1-1.jpg)

**准备工作：**

（1）删除默认小猫角色。

（2）添加角色 Cat Flying 和 Earth。

（3）删除默认白色背景，添加背景 Nebula。

**功能实现（用积木块实现下列描述的功能）：**

（1）点击绿旗，角色 Earth 的初始位置为（X=170，Y=120），并以每秒向右旋转 15 度的速度不停的转动。

（2）点击绿旗，舞台背景换成 Nebula，清除图形特效，并以每秒漩涡特效增加 25 的速度不停改变。

（3）点击绿旗，角色 Cat Flying 的初始位置为（X=-180，Y=-115），初始方向为 90 度，初始状态为显示，初始大小为 100，初始造型为 cat flying-a。

（4）角色 Cat Flying 说“返回地球”2 秒 ，面向地球以移动 5 步，大小减小 1 的速度向地球飞去，直到碰到地球为止。

（5）角色 Cat Flying 碰到地球后，隐藏，停止全部脚本。

**注意事项：**

- 功能（1）全部写在角色Earth代码区的【当绿旗被点击】积木下面。

- 功能（2）全部写在背景代码区的【当绿旗被点击】积木下面。

- 功能（3）（4）（5）全部写在角色CatFlying代码区的【当绿旗被点击】积木下面。

---

## 12-2 : 天使

> CCF GESP 2023年12月认证 图形化编程 1级试题

![12-2 - 天使](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-2023.12-1-2.jpg)

**准备工作：**

（1）删除默认小猫角色。

（2）添加角色 Wand 和 Fairy。

（3）删除默认白色背景，添加背景 Woods，并为背景添加音乐 Xylo1。

**功能实现（用积木块实现下列描述的功能）：**

（1）点击绿旗，背景换成 Woods，并循环播放背景音乐 Xylo1。

（2）点击绿旗，角色 Fairy 的初始位置为（X=-140，Y=-50），初始方向为 90 度，初始大小为 90。

（3）当 Fairy 被鼠标点击后，Fairy 会跟随鼠标指针移动。

（4）点击绿旗，角色 Wand 的初始位置为（X=140，Y=20），初始方向为 90 度，初始大小为 80，Wand 总保持在其他角色的前面。

（5）当碰到 Fairy，Wand 会吸附在 Fairy 上面。

**注意事项：**

- 功能（1）全部写在背景代码区的【当绿旗被点击】积木下面。

- 功能（2）全部写在角色Fairy代码区的【当绿旗被点击】积木下面。

- 功能（3）全部写在角色Fairy代码区的【当角色被点击】积木下面。

- 功能（4）（5）全部写在角色Wand代码区的【当绿旗被点击】积木下面。
