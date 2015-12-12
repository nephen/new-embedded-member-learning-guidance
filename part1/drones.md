# 无人机

####项目描述
---
以stm32为飞行控制平台，mpu6050或mpu6000为姿态传感器，采用最新姿态估计算法，实现对四旋翼的定点定高飞行。

####项目成员
---
*项目发起人*：11级计科张洪龙、11级通信张力军

*无人机爱好者*：12级网络[吴兴章](www.nephen.com)、12级通信吴静雯、12级通信周涛

*目前实验室参与人员*：13级通信曾显珣、13级计科贺艳丹、13级网络潘高鹏、14级廖臻瑀、14级计科刘英华

####项目进展
---
#####1、初学篇
[`匿名飞控`](http://www.anotc.com/)是国内有名的开源飞控，有完善的源代码支持，淘宝购件请到[匿名科创](https://item.taobao.com/item.htm?spm=a230r.1.14.30.5FDa0s&id=42276400719&ns=1&abbucket=7#detail)，这们会对硬件不太擅长的人有好处，可以认真研究飞行算法。

外国也有一个做微型四轴的，叫做[Crazyflie](https://www.bitcraze.io/)有兴趣可以多去参考一下别人的[源码](https://github.com/bitcraze)，淘宝购件[[地址1]](https://item.taobao.com/item.htm?spm=a1z10.5-c.w4002-5390404431.91.IKQiR6&id=41416472851)[[地址2]](https://shop35831139.taobao.com/?spm=a230r.7195193.1997079397.2.apEOxY)。

这里有个建议，花点时间学下[GIT](http://git-scm.com/doc)，然后将项目源码托管于[Github](https://github.com/)上，这对一个团队的项目管理有很大的好处，不会有项目里边谁的代码是最新的这样的疑问了。
#####2、加强篇
正在学习[px4](www.pixhawk.org)，硬件现成，主攻软件。

pixhawk`官方源码`托管在[www.github.com/px4/Firmware](www.github.com/px4/Firmware)上。

平时学习交流平台使用了[有道云协作](http://163.fm/cFX5pTQ)，欢迎加入群12591513。

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

*项目作品*：http://pan.baidu.com/s/1gdhSxHL *密码*：52ge

*2015省赛源码*:http://pan.baidu.com/s/1pJH4x0B  *密码*:4vag
