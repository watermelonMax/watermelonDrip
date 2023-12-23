---
title: "配置github blog"
date: 2023-11-28
draft: false
description: ""
tags: ["new", "docs"]
---

## 本地调试

1. 在发布到网站前可以在本地预览网站或内容的效果，运行命令：

```hugo server```

![hugo-server](https://cuttontail.blog/blog/create-a-wesite-using-github-pages-and-hugo/hugo-server.png)

2. `hugo server` 运行成功后，可以在 `http://localhost:1313/` 中预览网站

## 发布内容 

1. `hugo` 命令可以将你写的 Markdown 文件生成静态 HTML 网页，生成的 HTML 文件默认存放在 `public` 文件夹中。

![hugo-command](https://cuttontail.blog/blog/create-a-wesite-using-github-pages-and-hugo/hugo-command.png)

2. 推送**博客源仓库**的  `public` 文件夹中的 HTML 网页文件到 **GitHub Pages 仓库** 中

   ```cd public```

    

3. 将修改先提交至**博客源仓库**

```
git add .
git commit -m "...(修改的信息)"
git push origin main
```



如果没推上去，别忘了把vpn关了
