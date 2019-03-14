---
layout: single
title:  "Jekyll踩坑记"
date:   2019-03-14 11:34:31 +0800
---

# Github Pages + Jekyll 搭建个人博客

jekyll + Github pages 搭建个人博客这个方案就不再讨论了，这里只记录下需要的资料，和中间遇到的坑..

这些是有用的链接地址

+ [博客教程，直接照搬](https://github.com/qiubaiying/qiubaiying.github.io/wiki/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B)
+ [Github pages 教程](https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages)
+ [Minimal Mistakes 一个主题](https://mmistakes.github.io/minimal-mistakes/)

遇到的坑，按照时间顺序记录

+ 直接copy别人搞好的开始，这是最好最快的办法
+ 千万别gem直接安装jeklly, 不然bundle install会有gem的环境问题
+ images中放进去的图片，在jekyll s，localhost查看的时候可能显示不出来
+ favicon也可能导致错误，可以去[这个地址](https://realfavicongenerator.net/)直接生成，放到根目录，然后在[head/custom.html](../_includes/head/custom.html)这个文件配置
