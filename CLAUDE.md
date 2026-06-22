# CLAUDE.md

## 项目简介

这是 **Chengxin Zheng (郑诚信)** 的个人学术主页，基于 [Academic Pages](https://academicpages.github.io/) 模板构建，使用 Jekyll 静态网站生成器，部署于 GitHub Pages。

网站地址：https://chauncey-jheng.github.io

## 技术栈

- **静态网站生成器**：Jekyll (Ruby)
- **主题**：Academic Pages（基于 Minimal Mistakes）
- **部署**：GitHub Pages
- **样式**：Sass/SCSS

## 目录结构

```
├── _config.yml          # 全局配置（站点信息、作者信息、插件等）
├── _pages/              # 静态页面（About、CV、Publications 等）
├── _posts/              # 博客文章（Markdown）
├── _publications/       # 学术论文页面
├── _talks/              # 演讲页面
├── _teaching/           # 教学页面
├── _portfolio/          # 项目/作品集页面
├── _data/               # 数据文件（导航、简历等 YAML）
├── _includes/           # 可复用的 HTML 片段
├── _layouts/            # 页面布局模板
├── _sass/               # 样式文件
├── assets/              # JS、CSS、图片资源
├── images/              # 图片文件
├── files/               # 可下载文件（PDF 等）
└── markdown_generator/  # 从 TSV 生成 Markdown 的脚本
```

## 常用命令

### 本地预览

```bash
# 安装依赖
bundle install

# 启动本地服务器（访问 http://localhost:4000）
bundle exec jekyll serve -l -H localhost
```

### Docker 方式运行

```bash
docker compose up
```

## 内容管理

### 新增文章

在 `_posts/` 目录下创建文件，命名格式：`YYYY-MM-DD-title.md`，Front Matter 示例：

```yaml
---
title: '文章标题'
date: 2024-01-01
permalink: /posts/2024/01/blog-post-1/
tags:
  - tag1
  - tag2
---
```

### 新增论文

在 `_publications/` 目录下创建 Markdown 文件，Front Matter 示例：

```yaml
---
title: "论文标题"
collection: publications
category: conferences
permalink: /publication/2024-paper
date: 2024-01-01
venue: 'Conference Name'
paperurl: 'http://example.com/paper.pdf'
---
```

### 修改个人信息

编辑 `_config.yml` 中的 `author` 部分，修改姓名、简介、社交链接等。

### 修改导航栏

编辑 `_data/navigation.yml`。

### 修改简历

编辑 `_data/cv.yml`（如果存在）或对应的页面文件。

## 部署说明

- 推送到 `master` 分支后，GitHub Actions 会自动构建并部署
- 构建状态可在仓库的 Actions 页面查看

## 注意事项

- `_config.yml` 修改后需重启本地服务器才能生效
- 图片放在 `images/` 目录，可下载文件放在 `files/` 目录
- 所有内容页面使用 Markdown 格式编写
