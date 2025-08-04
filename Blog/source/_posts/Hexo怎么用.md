---
title: Hexo怎么用
date: 2025-08-04 22:10:44
tags:
comments: true 
---

<!-- more -->
## 一、相关命令

  | 功能                                      |                                 |
  | ------------------------------------------| ------------------------------ |
  | 首次初始化新博客项目                        |   hexo init ~       (~代表文件夹名字) |
  | 新建文章                                   |   hexo new ~   或  hexo n ~  |
  | 本地预览文章                               |   hexo server    或 hexo s       |
  | 生成静态文件                               |   hexo generate 或 hexo g        |
  | 部署到github                              |   hexo deploy    或 hexo d       |
  | 清除缓存文件                              |   hexo clean                     |
  | 显示版本信息                              |   hexo version  或 hexo v        |
  | 安装项目依赖(首次使用hexo最好安装)         |   npm install                    |
  


  命令可以用 && 来组合
  注意: 开始写文章前最好先用 hexo clean 清除一下旧的缓存文件


  表示截断 <!-- more -->

## 二、 _config.yml
        根目录配置文件 _config.yml
        这个文件位于 Hexo 的根目录






三、内容维护
   title: 文章的标题
   date: 文章的发布日期
   tags: 文章标签, 一个文章可以添加多个标签
   categories: 文章分类
   description: 文章的简短描述
   password: 访问文章的密码

 
   Git仓库应该有这些文件:   .gitignore
                          _config.yml(Hexo的全局配置文件)
                          package.json、package-lock.json、yarn.lock 
                          source/(文章、页面、图片等资源在此)
                          themes: 网站的主题在此



好用的主题: anzhiyu