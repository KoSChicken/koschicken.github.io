---
title: Hello?
date: 2015-09-09
tags: [扯淡, Jekyll]
categories: [扯淡]
math: true
---

千辛万苦终于把这个破烂博客给弄出来了。

此刻我的心情是崩溃的。

![bengkui][bengkui]

我感觉我可能把所有可能碰到的问题都碰到了...

先是在本地弄这个玩意，装个ruby，再装个rubygems，怎么装我就不想说了，都是泪。

免费的ss现在没法用了，国内ruby又那么难下，挣扎了半天，还是去买了个付费的ss账号，真辣鸡。

好不容易装好ruby环境，gem install jekyll的时候又悲剧了，被墙，辣鸡GFW。

搜索一番，改了淘宝的安装源，终于让劳资成功安装了jekyll。

然后终于成功的在本地启动了jekyll...

我泪流满面，完全不想再去弄样式了，先默认样式用着吧。

接下来就是上传github，我事先在github上弄了一个仓库，具体怎么起名什么的，github上有，不再赘述。

上传...

接着我就收到了github的邮件...

![githubmail1][githubmail1]

![jingya][jingya]

卧槽，怎么就build failure了？！这尼玛的提示能不能专业点，就给一句话然后丢个网址，辣鸡。

百度谷歌必应一起上，听说是Markdown的锅，于是把config里的markdown: kramdown改成markdown: redcarpet，再次提交。

果然我又收到了邮件...

![githubmail2][githubmail2]

![liulei][liulei]

然而还是build failure。噫，似乎有几个字不太一样。

啧啧啧，这次真是markdown的锅，怒删出问题的md文件。提交。

哦呵呵，终于不是404了。

![blog0][blog0]

![liulei][liulei]

那么，博客终于搭建完成。

![gui][gui]


[bengkui]:  {{"/20150909/bengkui.jpg" | prepend: site.imgrepo }}
[jingya]:  {{"/20150909/jingya.jpg" | prepend: site.imgrepo }}
[liulei]:  {{"/20150909/liulei.gif" | prepend: site.imgrepo }}
[githubmail1]:	{{"/20150909/githubmail1.jpg" | prepend: site.imgrepo }}
[githubmail2]:	{{"/20150909/githubmail2.jpg" | prepend: site.imgrepo }}
[blog0]:	{{"/20150909/blog0.jpg" | prepend: site.imgrepo }}
[gui]:	{{"/20150909/gui.jpg" | prepend: site.imgrepo }}