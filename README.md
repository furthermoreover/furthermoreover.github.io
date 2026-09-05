# 陈永斌的博客

基于 GitHub Pages + Jekyll 搭建的个人博客，免费托管，Markdown 写文章。

## 写文章

在 `_posts/` 下新建 `YYYY-MM-DD-标题.md`：

```markdown
---
layout: post
title: "标题"
date: YYYY-MM-DD
---
内容（Markdown）
```

push 到 main 分支后，GitHub Pages 会自动重新构建发布。

## 本地预览（可选）

```bash
bundle install
bundle exec jekyll serve
# 访问 http://127.0.0.1:4000
```
