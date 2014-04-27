---
layout: post
title:  菜鸟建博客
date:   2014-04-26
categories:
- Notes
tags:
- GitHub
---

突发奇想，突然想建一个博客，格式的话就凑合凑合算了，关键是想记录一点学习和生活中有意思的东西，也能稍微帮助进步。
先做一个测试吧：

```
hello world!
```
刚开始的话对github和jekyll不太了解，随着学习慢慢的深入，相信博客会有改观的。今天花了一天时间，搞成这样也很不错了。>.<只能默默的安慰自己了。下面是我学习的顺序：

- [Github Pages极简教程](http://yanping.me/cn/blog/2012/03/18/github-pages-step-by-step/)
- [使用Github Pages建独立博客](http://beiyuu.com/github-pages/#github)
- [像黑客一样写博客——Jekyll入门](http://www.soimort.org/posts/101/)
- [github help](https://help.github.com/)

不是太难，直接照着做就行了。建议Ubuntu下使用，会简单很多。

## Markdown

强烈建议学习[Markdown](https://daringfireball.net/projects/markdown/‎)。语法超级简单。有没有发现毕业设计的时候，排版还要花好长的时间，写个报告也要花好长时间，有了Markdown就不用担心了。就和百度的核心价值观一样：**简单可依赖**。
从别处抄来的Markdown优点如下：

- 纯文本，所以兼容性极强，可以用所有文本编辑器打开。
- 让你专注于文字而不是排版。
- 格式转换方便，Markdown 的文本你可以轻松转换为 html、电子书等。
- Markdown 的标记语法有极好的可读性。

也有中文版的文档，直接google就行了。正如某位大神所说：“这是一门可以学完的语言”。注意，说的是**语言**，能学完的可不多啊！
一起努力吧！！！

## github本地推送

本地的代码或者文档可以先写，有网的时候再传到github上（妈妈再也不用担心没网了）。
在项目的根目录下三个命令比较有用：

```
$ git add .#添加目录下全部文件
$ git commit -m ""#引号里是自己想要添加的更改信息
$ git push -u origin master#推送到master分支
```
刚开始的时候，我一直不知道`$ git commit -m ""`的引号里应该填哪些代码，后来表示我2了，里面是给自己看的，写上自己做的更改就行了，不写不知道有没有关系（没试过，觉得应该无所谓）。
出现错误的时候贴错误代码在网上查一下就行了，我一般用简单粗暴的`$ git push -f`。

先这样吧，以后有空再完善。

