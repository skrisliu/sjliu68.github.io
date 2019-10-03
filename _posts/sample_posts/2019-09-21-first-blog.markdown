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

I always wanted to create a personal website when I was still at campus. But back then I was saying to myself "you are too busy". This year, since january, except for two months in Chongqing, life became boring. Finally, it is time to create my website, in this 6 square-meter room.

大学还没有毕业的时候，就有建立个人网站的想法。那时候总是觉得自己太忙，结果今年自1月以来，除开暑假在重庆上了两个月的班，时间总是很充裕，却也被荒废掉。最终在这6平米的地方迈开了自己建站的第一步。

做的更像是个人网页而非个人网站，暂时还是托管在GitHub上，受GitHub每月10万流量的限制。有大流量需求的还是得买个托管服务器。

---

## Step 1: Create GitHub Pages

这一步推荐参考： [创建 GitHub Pages](https://zhuanlan.zhihu.com/p/58229299)

首先注册个GitHub，创建repository。注意，repo必须命名为"username.github.io"，这里我的username是stop68。

![Create GitHub Pages]({{site.baseurl}}/assets/img/y190921/a1.jpg)

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

---
## Step 3: Buy a Domain Name
购买一个域名，可以考虑在 GoDaddy namesilo namecheap 这几个域名代理商内购买，前面两家据说支持支付宝，我是通过namecheap购买的。GoDaddy历史最久，据说服务最差。

域名还是用姓名或是有意义的符号，尽管.com最常用，但所剩域名不多，反而个性域名受到青睐。如李飞飞，我觉得以下都是极好的，当然最好的还是"feifei.li"，这是li姓华人的福利了。

  >lifeifei.me
  
  >feifei.li
      
  >li.feifei.xyz

---
## Step 4: Link GitHub Pages with Your Domain
首先，在域名代理商里找到设置CNAME的地方。按照图示，设置4个Record，1个CNAME Record。

其中，CNAME Record的Valuey要更改为你的GitHub Pages域名，Host看你希望子域名是什么，正常情况下应该填写www。

![Link GitHub Pages and Your Domain]({{site.baseurl}}/assets/img/y190921/a3.jpg)

最后在GitHub Pages的设置里，找到Custom domain，修改为自己的网址，就完成了。