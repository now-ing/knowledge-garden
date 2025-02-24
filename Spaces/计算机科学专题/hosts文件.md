---
title: hosts文件
date created: 2022-06-15
date modified: 2022-07-05
---

hosts 是电脑、手机等设备中的一个本地系统文件，主要作用是解析域名（将网址指向服务器 IP 地址），而且优先于远程 [[DNS]] 服务，因此可以通过修改 hosts 文件屏蔽某个网址连网，来禁止访问某个网站。

也就是说，当访问一个网址时，会首先检索本地 hosts 文件，如果没有该网址的解析信息，才会访问远程 DNS 解析服务器。

有很多软件都是向其服务器发起请求，获取验证授权，所以有个很简单的方法就是改 hosts，将例如 yanzheng.com 域名，指向 127.0.0.1。这原理和广告屏蔽插件也有点类似，直接屏蔽某些广告域名的访问，网站为了可靠性，不会因为广告域名访问不通就让整个网站都打不开。
