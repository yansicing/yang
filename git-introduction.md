---
title: Git with Visual Studio Code
layout: post
categories: Git
tags: Git VS
excerpt: Visual Studio Code using Git

---
#### Visual Studio Code与Git <span id="home">
---

__持续更新（updating···）__

---
VS Code 集成了Git功能，并支持基本的git命令，这使得我们能够在开发过程方便的提交和获取代码
#### 操作步骤

##### 1. Git存储库初始化
* 新建工作目录`yang`
* 将`yang`添加到Resource manager中
* View-Command palette-Git:Initialize Repository

##### 2. 暂存和提交
* 显示Git输出：Show Git Output
* 点击+号暂存所有更改
* 提交到本地代码库

##### 3. 提交代码到Github

* Github新建代码仓库`yang`
* 在`yang`中打开Git Bash
* 配置用户名：`git config --global user.name "用户名"`
* 查看用户名：`git config user.name`
* 配置邮箱：`git config --global user.email "邮箱"`
* 查看邮箱：`git config user.email`
* 初始化本地仓库：`git init`
* 暂存已更改文件：`git add . `
* 提交所有文件：`git commit -m “备注信息”`













* ```git remote add origin https://github.com/yansicing/yang.git```
* ```git pull origin master```
* 代码合并后，最新的工作目录下面多了`LICENSE`和`README.md`
* 发布分支：Publish Branch
##### 4. 克隆远程仓库
* 工作目录克隆远程代码仓库，然后用Visual Studio Code 打开

#### Git命令






---

> 待完善（To be added~）

---


##### 参考文献 <span id="4">
- [fylstudio-Windows10和Visual Studio Code环境中配置使用Git和GitHub](https://blog.csdn.net/fylstudio/article/details/79106331)
- [捷风-git终端合并代码的简单使用](https://www.jianshu.com/p/220c6846badf)


---
##### **返回[顶部](#home)**