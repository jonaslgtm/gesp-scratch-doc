# GESP 图形化编程 1 级认证样题

> 更新完毕 .

## 样题01 : 踢足球

> GESP 图形化编程 1 级认证样题

![样题01 : 踢足球](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-sample-1-01.jpg)

**准备工作：**

(1) 选择背景 Playing Field。

(2) 删除默认小猫角色，添加角色 Ben、Jordyn 和 Soccer Ball。

**功能实现：**

（1）用积木实现 Jordyn 的初始位置为舞台左下角坐标为（-164，-81），初始造型为 jordyn-a，面向右侧，如图所示；

（2）用积木实现 Ben 的初始位置为舞台右上角坐标为（187，53），初始造型为ben-d，面向左侧，如图所示；

（3）用积木实现 Soccer Ball 位于 Jordyn 脚前不远处坐标为（-114，-119），面向 Ben；

（4）点击绿旗，Jordyn 每隔 1 秒切换一个造型，直至其造型为jordyn-d；（5）在切换成 jordyn-b 造型后，Soccer Ball 播放声音basketball bounce的同时向 Ben 移动，直到碰到 Ben 为止；

（6）当 Ben 碰到 Soccer Ball 后，Ben 说“好球”2 秒，终止本身程序；

**注意事项：**

- 本程序只允许使用运动、外观、事件（除广播）、控制、侦测类积木块。

---

## 样题02 : 海底寻宝

> GESP 图形化编程 1 级认证样题

![样题02 : 海底寻宝](https://cdn.jsdelivr.net/gh/jonaslgtm/Cloud-Image-Hosting/ccf-gesp/scratch/scratch-sample-1-02.jpg)

**准备工作：**

(1)导入背景 Underwater 2；

(2)删除默认小猫角色，导入角色 Crystal、Diver1 和Fish。

**功能实现：**

(1)点击绿旗，用积木实现潜水员的初始坐标为（-130，-125），面向舞台的右侧，钻石的初始坐标为（180，30）；

(2)点击绿旗，用积木实现小鱼在舞台的左侧，面向舞台的右侧，初始造型为fish-c，沿着水平方向不断游动，碰到边缘就反弹，且肚皮不能朝下；

(3)潜水员能够面向鼠标指针，以移动 10 步，等待 0.2 秒的速度在舞台上移动（通过移动鼠标指示方向，指引潜水员找到钻石）；

(4)在移动过程中，潜水员如果碰到钻石，那么就停止移动，说“找到钻石啦”2 秒，终止所有程序。

**注意事项：**

- 本程序只允许使用运动、外观、事件（除广播）、控制、侦测类积木块。
