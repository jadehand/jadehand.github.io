# JadeHand Blog

[![Hugo](https://img.shields.io/badge/Hugo-0.147.8+-blue.svg)](https://gohugo.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Website-jadehand.cn-brightgreen.svg)](https://jadehand.cn)

个人博客网站，基于 [Hugo](https://gohugo.io/) 静态网站生成器构建，使用 [Diary](https://github.com/AmazingRise/hugo-theme-diary) 主题。

## 🚀 特性

- 📝 **基于 Hugo** - 快速、灵活的静态网站生成器
- 🎨 **Diary 主题** - 优雅的设计，支持深色模式
- 📱 **响应式设计** - 完美适配移动端和桌面端
- 🌍 **多语言支持** - 支持中文和英文
- 🔍 **SEO 优化** - 内置 SEO 功能，便于搜索引擎收录
- 📊 **统计支持** - 可集成 Google Analytics
- 💬 **评论系统** - 支持多种评论系统
- ⚡ **快速加载** - 静态文件部署，加载速度快
- 🔒 **安全可靠** - 无服务器端代码，安全性高

## 📦 快速开始

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

### 本地开发

```bash
# 启动本地服务器
hugo server -D

# 访问 http://localhost:1313
```

### 构建部署

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
│       ├── welcome.md   # 欢迎文章
│       └── huaweionboardding.md  # 华为入职攻略
├── themes/              # 主题目录
│   └── diary/           # Diary主题
├── archetypes/          # 文章模板
│   └── default.md       # 默认模板
├── static/              # 静态资源
│   └── favicon.ico      # 网站图标
├── .github/             # GitHub Actions配置
├── hugo.toml            # Hugo配置文件
├── .gitignore           # Git忽略文件
├── README.md            # 项目说明
├── LICENSE              # 许可证
├── CNAME                # 自定义域名配置
└── .gitmodules          # Git子模块配置
```

## 🚀 部署

本项目使用 GitHub Actions 自动部署到 GitHub Pages。

### 部署流程

1. 推送代码到 `main` 分支
2. GitHub Actions 自动构建并部署
3. 访问地址：[https://jadehand.cn](https://jadehand.cn)

### 自定义域名

- 主域名：https://jadehand.cn
- 备用域名：https://jadehand.github.io

## 📝 写作指南

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
categories: "技术"
tags: "Hugo, 博客"
description: "文章描述"
author: "JadeHand"
showToc: true
TocOpen: false
weight: 1
---

文章内容...
```

### 文章分类

- **技术** - 技术分享、学习笔记
- **职场** - 工作经验、职场感悟
- **生活** - 生活随笔、个人思考

## 🛠️ 自定义配置

### 主题配置

主题配置文件：`themes/diary/theme.toml`

### 网站配置

主要配置在 `hugo.toml` 文件中：

- `baseURL` - 网站地址
- `title` - 网站标题
- `theme` - 使用的主题
- `params` - 自定义参数

### 样式自定义

如需自定义样式，可以：

1. 在 `static/css/` 目录下添加自定义 CSS 文件
2. 在 `layouts/` 目录下添加自定义模板
3. 修改主题的 SCSS 文件

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

### 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 📞 联系

- 🌐 网站：[https://jadehand.cn](https://jadehand.cn)
- 🐙 GitHub：[@jadehand](https://github.com/jadehand)
- 📧 邮箱：your-email@example.com

## 🙏 致谢

- [Hugo](https://gohugo.io/) - 静态网站生成器
- [Diary Theme](https://github.com/AmazingRise/hugo-theme-diary) - 博客主题
- [GitHub Pages](https://pages.github.com/) - 免费托管服务

---

⭐ 如果这个项目对你有帮助，请给它一个星标！