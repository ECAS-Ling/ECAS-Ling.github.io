# ECAS课题组主页编辑指南
教程参见[手把手教你用github制作学术个人主页](https://blog.csdn.net/qd1813100174/article/details/128604858)
## 编辑顶部菜单栏
编辑文件：_data\navigation.yml  
按照范例在文件中添加或删除标题

## 编辑左侧凌老师信息
编辑文件：_config.yml
修改文件中81-117行的信息

## 编辑每个菜单下的页面内容
在_pages目录下编辑/添加.md或者.html文件，我把所有编辑/添加的文件放到_pages/my_pages目录下。

注意把以下代码添加到每个文件的开头，并与_data\navigation.yml中的菜单栏名字对应
```
---
permalink: /RISC-V/
title: "RISC-V"
author_profile: true
---
```
所有页面中需要用到的图片都放在_image目录下，写md或者html时引用它的相对地址。

*Latest edit: 2024.4.8*