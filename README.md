# 神社的储物间

>点击访问：<http://mxts.jiujiuer.xyz>。

一个简单的PHP博客。内含车万要素（  
说下为啥写这个吧（）之前用WordPress那会主题有点问题，**没法评论，而且数据迁移比较麻烦，同时感觉mysql略有笨重**，这才下决心换成了hexo。然而安装上之后，发现空间占用貌似比较大，而且也有各种不尽人意的地方。正巧那会刚接触PHP，在用PHP升级我以前的一个静态站（神社的储物间，全是纯手写的html）。于是就决定把博客合并到储物间那个静态站里，顺便也是为了学习PHP。  

于是就越写越多，成了这个博客（笑）

## 特性

作为一个不怎么喜欢数据库的人，我果断没有用任何数据库。我转向了markdown，并借鉴了hexo的魔改md思想（雾），把文章信息、文章内容、评论区都塞到了一个markdown文件里。
* 无数据库，开箱即用
* 支持markdown（不过是类似于hexo那样魔改的格式）
* 在线编辑(很简陋，后面完善下)
* 文章管理、数据统计（总字数，文章总数、标签数。后面添加更多信息）
* 文章评论（数据以特殊格式保存在该文章尾部）

## 使用教程

默认密码为1672，登录入口默认打开。详情见自带文章。
注意：**不要在文章中使用--------，否则会被误识别为文章结束！**

## 开发计划（咕

* 搜索文章（完成）
* 更好的CSS样式（完成？）
* 文件管理（完成）
