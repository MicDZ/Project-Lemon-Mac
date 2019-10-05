# Project_lemon_Mac

一个在Mac下安装project_lemon的解决方案

本项目已不适用于linux

# 使用方法

1. 安装qt

没有安装brew的可以先安装一下

> brew install qt

2. 编译
在源代码目录下

> gcc watcher_unix.c -o watcher_unix -O2
>
> gcc realjudge.c -o realjudge_linux -O2

3. 生成

> qmake lemon.pro
>
> make

然后直接双击运行源代码目录下的lemon

如果要更改图标可以百度
