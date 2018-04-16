---
title: Hexo使用
date: 2018-04-16 11:58:27
tags:
---

### 第一步安装
npm install -g hexo-cli

### 第二步：建站
    hexo init <folder>
    cd <folder>
    npm install

### 写文章
    hexo new [layout] <title>
    hexo new draft "测试"

### 写草稿
    hexo new draft "测试draft"      写草稿
    hexo publish draft "测试draft"  发布草稿

### 配置文件在_config.yml 中查看
    配置好git仓库
    deploy:
        type: git
        repo: git@github.com:DaiWenqi/DaiWenqi.github.io.git

### 生成静态
    hexo generate

###　部署
    hexo generate

### 备份源码流程
    git init
    git add 需要备份的文件
    git commit -m 'hexo使用'
    git push

### 检查源码修改并提交
    git status

    use "git add/rm <file>..." to update what will be committed
    选择需要跟踪的文件

> [git - 简易指南](http://www.bootcss.com/p/git-guide/)

配置文件在_config.yml 中查看