# Hugo 博客

**yml定义文章相关信息**

常用的信息如下：

```yml
---
title: "标题"
date: "2020-08-07"
tags:
  - java
categories:
  - 随笔
---
```

更多信息配置，例如：

```yml
---
title: "标题"
date: "2020-08-07"
description: 文章摘要
# 隐藏目录
hideToc: false
#生成目录
enableToc: true
# 博客展示目录
enableTocContent: true
author: 作者
authorEmoji: 🤖
tags:
  - 标签
categories:
  - 分类
series:
  - 系列
---
```

**hugo部署博客相关命令**

1. 本地预览`hugo server`，浏览器访问`http://localhost:1313`即可
2. 部署到GitHub或Gitee，`hugo -D`