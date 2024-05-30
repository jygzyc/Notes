---
title: Ecool的知识花园
template: home.html
comments: false
---

本站点基于[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)进行部署，一部分文章来源于之前的博客。

可以通过[note.lilac.fun](https://note.lilac.fun/)可以访问本站点，基于[Github Pages](https://pages.github.com/)，国内访问会有一定的延迟。

## 记录

在之前几年时间里，折腾过`Hexo`，`Hugo`，甚至还开发过相关的插件，搞过不同的留言系统，也搞过不同的相册，但是最后还是打算回归简洁。

在自建服务器到期了之后，因为也没有其他使用服务器的需求，又回归了Github，在一次无意中发现了`Mkdocs`，并喜欢上了它简洁的风格。下定决心，将之前无用的部分去除，重新建立站点。

未来，希望可以一直记录下去，把这里作为一个起点。

## 技术

本站参考[维燕的知识花园](https://weiyan.cc/)，使用了`Mkdocs` + `Github Discussions`的方式，在原作者的基础上做了少许修改，减少了一部分处理不同页面中重复的步骤，重点的代码都有注释，可以用来部署其他站点

`nav.json`中放了全站的router，使用`nav2pages.py`进行转化，这里的标签使用两位一个分类，逐步估计应该是够用了（不够用再改），对应了discussion的各级分类和标签，具体可以参考一下`discussionFileConverter.py`的代码

## 联系

个人现在使用比较多的是邮箱，可以直接联系[jyg.zyc@outlook.com](mailto:jyg.zyc@outlook.com)

## 致谢

感谢[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)，让我认识了一个非常简洁和好看的博客主题，并能够很快在社区解决部署时出现的问题。

感谢[维燕的知识花园](https://weiyan.cc/)，让我学习了如何使用 Github discussions 建立博客站点。












