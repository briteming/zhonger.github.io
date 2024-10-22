---
layout: post
title: '在windows上，安装ruby'
date: 2024-10-21 16:48
categories: others
author: brite
tags:
- 随笔
- 程序
---

## 在windows上，安装ruby

首先访问https://rubyinstaller.org/downloads/，得到RubyInstaller的下载地址：
https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-3.3.5-1/rubyinstaller-devkit-3.3.5-1-x64.exe

下载后，安装它。然后设置环境变量：
 按win+r键，输入sysdm.cpl ，回车。然后点击“高级”-“环境变量”。在环境变量对话框的下半部（系统变量部分），点击PATH那行，然后点击下方的“编辑”按钮，打开“编辑环境变量”对话框，然后点击“新建”按钮，在蓝色空白栏处输入某个可执行文件所在的路径，比如：c:\Program Files\Ruby33-x64\bin ，
然后点击“确定”按钮。-“确定”-“确定”即可。
新开一个终端程序（比如git-bash.exe),添加的环境变量就生效了。

然后，即可运行命令：gem install jekyll ，来安装jekyll.
