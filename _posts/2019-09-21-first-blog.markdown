---
layout: post
title: My First Blog - Create Personal Website with GitHub Pages
date: 2019-09-21 09:46:34 +0300
description: Teach you how to create personal website in 30 minutes. # Add post description (optional)
img: rainbow.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [GitHub Pages, Personal Website]
---
Every day counts.

大学还没有毕业的时候，就有建立个人网站的想法。那时候总是觉得自己太忙，结果今年自1月以来，除开暑假在重庆上了两个月的班，时间总是很充裕，却也被荒废掉。最终在这6平米的地方迈开了自己建站的第一步。

做的更像是个人网页而非个人网站，暂时还是托管在GitHub上，受GitHub每月10万流量的限制。有大流量需求的还是得买个托管服务器。

---

## Step 1: 创建 GitHub Pages

这一步推荐参考： [创建 GitHub Pages](https://zhuanlan.zhihu.com/p/58229299)

首先注册个GitHub，创建repository。注意，repo必须命名为"username.github.io"，这里我的username是stop68。

![创建 GitHub Pages]({{site.baseurl}}/assets/img/y190921/a1.jpg)

在repo的settings里找到GitHub Pages的选项，默认应该是启动的。可以勾选"Change Theme"找一些GitHub默认的模板。GitHub自带的是Jekyll，在我看来是框架，自称是"简单静态博客网站生成器"。

也可以到知乎或GitHub搜一些Jekyll的框架，folk后把他们命名为"username.github.io"。

完成后，你应该可以用以下域名登录到自己的GitHub Pages了，记得把username换成自己的用户名。

  >username.github.io

---
## Step 2: How to Git

学会Git能方便很多，打码总是舒服的。

首先，下载安装Git这个软件。成功以后，应该能在cmd下执行git的命令。

第二，在本地电脑选择一个文件夹作为以后存放个人网页的地方，执行以下命令，记得把两个username换成自己的。

  ```
  git clone https://github.com/username/username.github.io
  ```

现在，我就是在本地更新网页，然后再执行以下命令，push回GitHub上，注意comments部分是注释。

  ```
  git add . 
  git commit -m "comments" 
  git push origin master 
  ```

