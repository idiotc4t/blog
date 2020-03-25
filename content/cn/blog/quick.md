---
title: "Quick"
date: 2020-03-25T13:48:32+08:00
draft: false
weight: 0
enableToc: true
tocLevels: ["h2", "h3", "h4"]
---

# 快速使用Hugo R

快速创建文章

```shell
hugo new cn/blog/文章名.md
```

可以为文章建立标签
```md

<!-- 文章头的位置 toml格式 -->

tags = [
    "emoji",
]

```

本地启动博客

```shell
hugo server
```

配置完成后部署你的博客，首先你得在类unix系统下...

```shell
./deploy.sh

# 首先需要配置脚本里的2个变量
# 之后需要输入两次帐号和密码
# 如果配置的是gitssh形式的，配置完密钥，可免输入
```