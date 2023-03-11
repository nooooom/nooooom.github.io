---
title: IntelliJ IDEA 安装后的一些配置
key: a_20230210_01
tags: 开发工具
modify_date: 2023-02-10
---

IntelliJ IDEA 的一些使用技巧，截图版本号是 2022.3.2

<!--more-->

## 一、初始化配置

### 1、Ctrl + 滚轮缩放字体

```Editor```->```General```，平时不开启，需要的时候打开。

![image-20230210130731271](/images/20230210/image-20230210130731271.png)

### 2、自动导包

```Editor```->```General```->```Auto Import```，**必须开启**。

![image-20230210131851755](/images/20230210/image-20230210131851755.png)

### 3、显示行号和方法分隔符

```Editor```->```General```->```Appearance```，**必须开启**。

![image-20230210132223911](/images/20230210/image-20230210132223911.png)

### 4、代码提示

```Editor```->```General```->```Code Completion```，**必须开启**。

![image-20230210132659446](/images/20230210/image-20230210132659446.png)

![image-20230210133149169](/images/20230210/image-20230210133149169.png)

### 5、文件编码

```Editor```->```File Encodings```，都设置为 **UTF-8**。

![image-20230210133612248](/images/20230210/image-20230210133612248.png)

### 6、自动编译

```Build```->```Compiler```，**必须开启**。

![image-20230210134029769](/images/20230210/image-20230210134029769.png)

### 7、Maven

```Build```->```Build Tools```->```Maven```，**必须配置**，设置为正确的版本、配置文件和仓库地址。

![image-20230210135120767](/images/20230210/image-20230210135120767.png)

## 二、去掉 SQL 语法检查

### 1、去掉语法检查

```Editor```->```Inspections```，取消勾选下面两项。

![image-20230210140702718](/images/20230210/image-20230210140702718.png)

### 2、去掉背景色

```Editor```->```Color Scheme```->```General```->```Code```->```Injected language fragment```，取消勾选背景色。

![image-20230210141041675](/images/20230210/image-20230210141041675.png)

### 3、Before & After

修改前：

![image-20230210135835418](/images/20230210/image-20230210135835418.png)

修改后：

![image-20230210141423685](/images/20230210/image-20230210141423685.png)

## 三、新工程配置

这里需要将“一”中的 5、6、7 和“二”中的1再设置一遍。

![image-20230210134330565](/images/20230210/image-20230210134330565.png)
