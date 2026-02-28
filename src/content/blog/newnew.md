---
title: '如何在 Astro Theme Pure 中创建博客文章'
description: '本指南将详细介绍如何在 Astro Theme Pure 中发布一篇新的博客文章。'
publishDate: '2023-10-27'
author: '您的名字'
cover: '/blog/how-to-create-a-post/cover.jpg' # 封面图片路径
coverAlt: '键盘上的手，示意写作'
tags: ['Astro', 'Theme Pure', '指南', '博客']
draft: false
---

# 欢迎学习如何在 Astro Theme Pure 中创建文章！

本篇文章将指导您完成在 Astro Theme Pure 主题中发布新博客文章的整个过程。

## 第一步：创建文件

首先，您需要在 `src/content/blog/` 目录下创建一个新的 Markdown 或 MDX 文件，例如 `my-new-post.md`。

## 第二步：添加 Frontmatter

每篇文章都需要添加 YAML Frontmatter，它包含了文章的元数据。

```yaml
title: '您的文章标题'
description: '文章的简短描述。'
publishDate: 'YYYY-MM-DD'
author: '您的名字'
cover: '/path/to/cover.jpg'
coverAlt: '封面图片描述'
tags: ['标签一', '标签二']
draft: false