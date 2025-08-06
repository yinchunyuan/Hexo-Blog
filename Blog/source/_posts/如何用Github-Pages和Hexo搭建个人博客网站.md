---
title: 如何用Github-Pages和Hexo搭建个人博客网站
date: 2025-08-04 22:09:59
tags:
comments: true
---


<!-- more -->
# 如何用Github.Pages和Hexo搭建个人博客网站

## 来迟的文章
###  一.
       首先在Github上fork Hexo 和 Github.Pages仓库(这个步骤倒也不是必须的)
       链接:   Hexo: [GitHub](https://github.com/hexojs/hexo)   
               Github.Pages[Github](https://github.com/academicpages/academicpages.github.io)


###  二. 具体步骤  (前置: 安装Node.js、git, 注册github账号)
   第一步 进入Hexo项目根目录                cd Hexo
   第二步 拉取最新代码(确保与远程repo一样)   git pull origin main (如果主分支为main)
   第三步 创建或编辑文章                    hexo new "~"
   第四步 本地预览文章                      hexo server
   第五步 生成静态文件                      hexo generate    生成到public/目录
   第六步 部署到Github Pages                hexo deploy       自动推送到github.io



### 三. 
   Hexo是个简单、功能强大的博客框架
   使用 npm 安装 Hexo
   只显示文章标题, 不显示文章内容, 用<!-- more -->手动截断
   


### 四. Jekyll 静态站点生成器