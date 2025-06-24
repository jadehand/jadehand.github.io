# JadeHand Blog

个人博客网站，基于 [Hugo](https://gohugo.io/) 静态网站生成器构建。

## 🚀 特性

- 📝 基于 Hugo 静态网站生成器
- 🎨 使用 Diary 主题，支持深色模式
- 📱 响应式设计，支持移动端
- 🌍 多语言支持
- 🔍 SEO 优化
- 📊 支持 Google Analytics
- 💬 支持多种评论系统

## 📦 安装

### 前置要求

- [Hugo Extended](https://gohugo.io/installation/) (推荐版本 0.80.0+)
- [Git](https://git-scm.com/)

### 克隆项目

```bash
git clone https://github.com/jadehand/jadehand.github.io.git
cd jadehand.github.io
```

### 安装主题

```bash
git submodule update --init --recursive
```

## 🛠️ 开发

### 本地开发

```bash
# 启动本地服务器
hugo server -D

# 访问 http://localhost:1313
```

### 构建

```bash
# 构建静态文件
hugo

# 构建并压缩
hugo --minify
```

## 📁 项目结构

```
jadehand_blog/
├── content/              # 博客内容
│   ├── about.md         # 关于页面
│   └── posts/           # 文章目录
│       └── welcome.md   # 欢迎文章
├── themes/              # 主题目录
│   └── diary/           # Diary主题
├── archetypes/          # 文章模板
│   └── default.md       # 默认模板
├── .github/             # GitHub Actions配置
├── hugo.toml            # Hugo配置文件
├── .gitignore           # Git忽略文件
├── README.md            # 项目说明
├── LICENSE              # 许可证
└── .gitmodules          # Git子模块配置
```

## 🚀 部署

本项目使用 GitHub Actions 自动部署到 GitHub Pages。

- 推送代码到 `main` 分支
- GitHub Actions 自动构建并部署
- 访问地址：https://jadehand.github.io

## 📝 写作

### 创建新文章

```bash
hugo new posts/my-new-post.md
```

### 文章格式

```markdown
---
title: "文章标题"
date: 2024-01-01
draft: false
categories: ["技术"]
tags: ["Hugo", "博客"]
---

文章内容...
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License

## 📞 联系

- 网站：https://jadehand.github.io
- GitHub：[@jadehand](https://github.com/jadehand)