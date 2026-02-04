---
title: '博客操作指南'
description: '如何使用 Obsidian 编写和发布博客文章'
pubDate: 2026-02-04
tags: ['教程', '博客']
---

# 博客操作指南

## 写文章

### 1. 创建新文章

在当前文件夹创建新的 `.md` 文件，文件名建议用英文，如 `my-first-post.md`

### 2. 添加文章信息

每篇文章开头需要添加以下格式的信息：

```yaml
---
title: '文章标题'
description: '文章简短描述'
pubDate: 2026-02-04
tags: ['标签1', '标签2']
---
```

### 3. 编写内容

在 `---` 下方开始写正文，支持标准 Markdown 语法：

- `# 标题` - 一级标题
- `## 标题` - 二级标题
- `**粗体**` - **粗体**
- `*斜体*` - *斜体*
- `[链接](url)` - 链接
- `` `代码` `` - 行内代码
- 代码块用三个反引号包裹

---

## 发布文章

写完后，打开终端执行：

```bash
cd ~/Claude\ Cowork/blog && git add . && git commit -m "新文章" && git push
```

等待 1-2 分钟后访问博客查看更新。

---

## 常用链接

- 博客地址：https://iatnit.github.io/luckyclawd/
- GitHub 仓库：https://github.com/iatnit/luckyclawd

---

## 文件说明

| 路径 | 用途 |
|------|------|
| `src/content/blog/` | 博客文章 |
| `src/consts.ts` | 博客标题、描述 |
| `src/styles/global.css` | 样式 |
| `src/pages/about.astro` | 关于页面 |
