---
layout: post
title:  "Word2016停止工作问题"
date:   2016/9/7 星期三 11:31:35 
categories: Office
tags: Office Word
author: Kevin Lee
---

* content
{:toc}

解决Word2016停止工作的问题。




## 方法一

1. 搜索“Normal.dot”；
2. 找到路径 `%USERPROFILE%\AppData\Roaming\Microsoft\Templates` 下的“Normal.dot”文件，然后将其删除即可。

## 方法二

1. 打开注册表（regedit）
2. 找到如下路径：
	`HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Word`
	`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\Word\Addins`
3. 将上面两个文件夹word和addins重命名为word2和Addins2即可。