---
title: 如何用Github-Pages和Hexo搭建个人博客网站
date: 2025-08-04 22:09:59
tags:
comments: true
---


<!-- more -->
# 如何用Github.Pages和Hexo搭建个人博客网站

## 来迟的文章
###  一. 前置: 安装Node.js、git, 注册github账号
#### 1. 使用 npm 全局安装 Hexo CLI 
      命令: npm install -g hexo-cli 

#### 2. 初始化博客(在新文件夹下)
      命令: hexo init XXX
            cd XXX
            npm install (安装依赖)

#### 3. 联系到 Github
      命令: npm install hexo-deployer-git --save
      改一下 XXX 目录下的 _config.yml, 在最后的 deploy 那块增加一下自己的 github 信息
     

###  二. 具体步骤  
   第一步 进入Hexo项目根目录                cd Hexo
   第二步 拉取最新代码(确保与远程repo一样)   git pull origin main (如果主分支为main)
   第三步 创建或编辑文章                    hexo new "~"
   第四步 本地预览文章                      hexo server
   第五步 生成静态文件                      hexo generate    生成到public/目录
   第六步 部署到Github Pages                hexo deploy       自动推送到github.io
   (清除生成的旧文件: hexo clean, 最好每次在生成文章前都用一下)


### 三. 其他
   Hexo是个简单、功能强大的博客框架
   使用 npm 安装 Hexo


其他; 
2025-8-20 周三
最近遇到的问题主要是域名回退, 每次写完文章后总是回退到.github.io 域名, 还没找出怎么改

2025-8-21 周四 21:50
自己写的ci, 运行失败