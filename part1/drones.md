# 无人机

####项目描述
---
以stm32为飞行控制平台，mpu6050或mpu6000为姿态传感器，采用最新姿态估计算法，实现对四旋翼的定点定高飞行。

####项目成员
---
*项目发起人*：11级计科张洪龙

*无人机爱好者*：12级网络吴兴章、12级通信吴静雯

*目前实验室参与人员*：13级通信曾显珣、13级计科贺艳丹

####项目进展
---
#####1、初学篇
[`匿名飞控`](http://www.anotc.com/)是国内有名的开源飞控，有完善的源代码支持，淘宝购件请到[匿名科创](https://item.taobao.com/item.htm?spm=a230r.1.14.30.5FDa0s&id=42276400719&ns=1&abbucket=7#detail)
#####2、加强篇
正在学习[px4](www.pixhawk.org)，硬件现成，主攻软件。

pixhawk[官方源码](www.github.com/px4/Firmware)托管在www.github.com/px4/Firmware上。

######怎么加入开源飞控
```sh
~ $ git clone git@github.com:px4/Firmware.git
~ $ cd Firmware
~/Firmware $ make
```
######怎么使用GIT>>>[Git教程-廖雪峰的官方网站](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/)
```sh
~ $ sudo apt-get install git-all
~ $ makedir YuningFly
~ $ cd YuningFly
~/YuningFly $git init
~/YuningFly $git add *
~/YuningFly $git commit -m "Commit message"
~/YuningFly $git remote add origin git@github.com:{{username}}/{{repository}}
~/YuningFly $git push -u origin master
```
####项目源码
---
*git地址*：[www.github.com/nephen/MyFirmware](www.github.com/nephen/MyFirmware)

*百度云盘*：http://pan.baidu.com/s/1gdhSxHL *密码*：52ge
