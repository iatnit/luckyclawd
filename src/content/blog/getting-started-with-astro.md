---
title: 'Astro 入门指南'
description: '快速了解如何使用 Astro 构建博客'
pubDate: 2026-02-03
tags: ['Astro', '教程']
---

# Astro 入门指南

Astro 是一个用于构建快速、内容驱动网站的 Web 框架。

## 安装

```bash
npm create astro@latest
```

## 项目结构

```
/
├── public/          # 静态资源
├── src/
│   ├── components/  # 组件
│   ├── content/     # 内容（博客文章等）
│   ├── layouts/     # 布局
│   └── pages/       # 页面
└── astro.config.mjs # 配置文件
```

## 创建文章

在 `src/content/blog/` 目录下创建 `.md` 或 `.mdx` 文件即可。

## 本地开发

```bash
npm run dev
```

访问 `http://localhost:4321` 查看效果。

## 构建部署

```bash
npm run build
```

构建后的文件在 `dist/` 目录下。
