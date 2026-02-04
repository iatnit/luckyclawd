# Yun's Blog

基于 [Astro](https://astro.build/) 构建的个人博客。

## 快速开始

```bash
# 安装依赖
npm install

# 本地开发
npm run dev

# 构建
npm run build
```

## 添加文章

在 `src/content/blog/` 目录下创建 `.md` 文件：

```markdown
---
title: '文章标题'
description: '文章描述'
pubDate: 2026-02-04
tags: ['标签1', '标签2']
---

文章内容...
```

## 部署

推送到 GitHub 后会自动通过 GitHub Actions 部署到 GitHub Pages。
