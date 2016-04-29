# 无人机

[![Gitter](https://badges.gitter.im/nephen/YuningFly.svg)](https://gitter.im/nephen/YuningFly?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

####项目描述
---
以stm32为飞行控制平台，mpu6050或mpu6000为姿态传感器，采用最新姿态估计算法，实现对四旋翼的定点定高飞行。

####项目成员
---
*项目发起人*：11级计科张洪龙、11级通信张力军

*无人机爱好者*：12级网络[吴兴章](http://www.nephen.com/)、12级通信吴静雯、12级通信周涛

*目前实验室参与人员*：13级通信曾显珣、13级计科贺艳丹、13级网络潘高鹏、14级廖臻瑀、14级计科刘英华

####项目进展
---
####1.0 初学篇
*介绍*：[`匿名飞控`](http://www.anotc.com/)是国内有名的开源飞控，有完善的源代码支持，淘宝购件请到[匿名科创](https://item.taobao.com/item.htm?spm=a230r.1.14.30.5FDa0s&id=42276400719&ns=1&abbucket=7#detail)，这们会对硬件不太擅长的人有好处，可以认真研究飞行算法。另外还有如[crazepony](http://www.crazepony.com/)可以参考一下，这个飞控应该参考了[cleanflight](https://github.com/cleanflight/cleanflight)，有兴趣的都可以去了解一下。

外国也有一个做微型四轴的，叫做[Crazyflie](https://www.bitcraze.io/)有兴趣可以多去参考一下别人的[源码](https://github.com/bitcraze)，淘宝购件[[地址1]](https://item.taobao.com/item.htm?spm=a1z10.5-c.w4002-5390404431.91.IKQiR6&id=41416472851)[[地址2]](https://shop35831139.taobao.com/?spm=a230r.7195193.1997079397.2.apEOxY)。

*知识*：一般采用超声波、声纳或气压计来定高，定点可以看看[px4flow](https://pixhawk.org/zh/modules/px4flow)光流计([资料](http://bbs.elecfans.com/jishu_484076_1_1.html))。

*建议*：这里有个建议，花点时间学下[GIT](http://git-scm.com/doc)，然后将项目源码托管于[Github](https://github.com/)上，这对一个团队的项目管理有很大的好处，不会有项目里边谁的代码是最新的这样的疑问了。

####2.0 加强篇
*计划*：正在学习[px4](http://www.pixhawk.org/)，硬件现成，主攻软件。软件分为两套，一个为[原生代码](https://pixhawk.org/zh/modules/px4flow)，另一个基于px4飞行栈的[APM](https://github.com/diydrones/ardupilot)。

*分析*：整体来看，原生代码结构更加清晰，但是逻辑性强，APM对于入门者更加简单。但它们都可以用于pixhawk硬件上。

*资源*：平时学习交流平台使用了[有道云协作](http://163.fm/cFX5pTQ)，欢迎加入群12591513。或者加入本文上面的Gitter进行交流。

按照基础程度进行推荐，尽量推荐人人皆可阅读的一般性[文章](http://blog.exbot.net/archives/1169)，最后附上网盘链接。

*视频集*：

这里有一个飞控视频的讲解，感觉还不错，网盘资料在项目源码里给出了，可以参考一下，名字叫[飞控漫谈](http://v.youku.com/v_show/id_XMTUyNTI0NDc2MA==.html?f=26204012&from=y1.2-3.4.6)。

{% youtube %}https://www.youtube.com/watch?v=8m4_NpTQn0E&vq=hd720{% endyoutube %}

{% youtube %}https://www.youtube.com/watch?v=LnUmYgAINBc&vq=hd720{% endyoutube %}

{% youtube %}https://youtu.be/0Jpq6DU_HVg{% endyoutube %}

#####2.1 学习PX4进度条
这里主要展示项目的一个进展，同时会给出相应的链接，让新手也能循序渐进。

[无人机学习概览](http://www.nephen.com/arrange/drones) >>>>> [yuningfly开发](https://github.com/nephen/YuningFly)

####项目资源
---
*git地址*：[www.github.com/nephen/MyFirmware](https://www.github.com/nephen/MyFirmware)

*项目作品*：http://pan.baidu.com/s/1gdhSxHL *密码*：52ge

*2015省赛源码*: http://pan.baidu.com/s/1pJH4x0B  *密码*:4vag

*开源飞控源码（匿名）*：http://pan.baidu.com/s/1eRzfUj4

*飞控漫谈网盘*：http://pan.baidu.com/s/1qXFMpfI#path=%252F%25E9%25A3%259E%25E6%258E%25A7%25E6%25BC%25AB%25E8%25B0%2588%252F%25E7%25AC%25AC6%25E8%25AE%25B2

*yuningfly开发地址*: https://github.com/nephen/YuningFly