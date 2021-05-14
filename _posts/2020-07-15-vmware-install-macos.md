>---
layout: post
title: vmware install macos
subtitle: 虚拟机安装mac
date: 2020-07-15
author: samll_ant
header-img: img/mac/mac.jpg
catalog: true
tags:
    - vmware
    - mac
---

>**白嫖macos** 在vmware中安装mac，不用mac电脑也能使用mac系统

## 先上效果图

![pic](https://xingmegshuo.github.io/img/mac/mac1.png)

## 安装过程
- first  安装vmware unlocker
> 1.安装vmware unlocker 以支持vmware识别mac os 镜像
<br>2. wget 下载unlocker wget https://github.com/paolo-projects/unlocker/releases/download/3.0.3/unlocker.zip
<br>3. run ./lnx-install.sh
<br>4. python3 unlocker.py



- second 创建vmware虚拟机
> 1.格式化磁盘分区格式为AFPS
<br>2.进入命令终端修改日期输入 date 062614102014.30
<br>3.系统正常安装
<br>4.显示分辨率不正常问题解决 [参考链接](https://blog.csdn.net/SSS_Benjamin/article/details/89295692)
<br>5.下载vmwaretool.iso 开机挂载，再系统中安装,-----大工告成

## 现在 - 我的mac
![pic](https://xingmegshuo.github.io/img/mac/mac2.png)

## 最后 - 镜像资源

[os10.14.6.iso](https://pan.baidu.com/s/1VEo5rjCPzl9m783OIqs8KA)提取码: abcd 
[vmware tool.iso](https://pan.baidu.com/s/1TlzOW_C93qXpdEsP_yvpXQ) 提取码: abcd 