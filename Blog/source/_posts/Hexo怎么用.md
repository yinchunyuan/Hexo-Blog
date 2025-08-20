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


## 二、 _config.yml
        根目录配置文件 _config.yml
        这个文件位于 Hexo 的根目录


## 三、内容
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
但我用的主题是 hexo-theme-wang 这个


2025-8-14 周四
激动, 自己买了域名, 托管到 GithubPages 上,  直接就有 SSL 证书啦,  原来在 GithubPages 上托管的网站直接就有证书
白天瞎忙活半天...


2025-8-20 周三 21:29
看一下主题怎么改:  1.想把主题改成全面的星星, 中间没有分割线
                 2. 主题上面的栏删除一部分
   
看博主的配置方案, 有了头绪

