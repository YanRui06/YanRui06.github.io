# Zephyr的技术博客

![Hugo](https://img.shields.io/badge/Hugo-0.147-blue.svg)
![Theme](https://img.shields.io/badge/Theme-PaperMod-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

## 🌟 简介

这是我的个人技术博客，基于 Hugo 静态网站生成器和 PaperMod 主题构建。在这里分享我的技术学习笔记、项目经验和编程心得。

## 🚀 特性

- ✨ 现代化科技风格首页
- 📝 技术文章分享
- 🗂️ 文章归档功能
- 🚀 项目展示页面
- 📱 响应式设计
- 🌙 深色/浅色主题切换
- 🔍 搜索功能
- 📊 自动化部署

## 🛠️ 技术栈

- **静态网站生成器**: Hugo
- **主题**: PaperMod
- **部署**: GitHub Pages
- **CI/CD**: GitHub Actions
- **域名**: zephyr-rain.top

## 📁 项目结构

```
YanRui06.github.io/
├── .github/workflows/     # GitHub Actions 工作流
├── archetypes/           # Hugo 内容模板
├── content/              # 网站内容
│   ├── posts/           # 博客文章
│   ├── projects/        # 项目展示
│   ├── about/           # 关于页面
│   ├── archives.md      # 归档页面
│   └── landing.md       # 引导页面
├── layouts/             # 自定义布局
├── static/              # 静态资源
├── themes/PaperMod/     # 主题文件
├── config.yaml          # 网站配置
├── CNAME               # 自定义域名
└── README.md           # 项目说明
```

## 🚦 本地开发

### 环境要求
- Hugo >= 0.147.0
- Git

### 运行步骤

1. **克隆项目**
   ```bash
   git clone https://github.com/YanRui06/YanRui06.github.io.git
   cd YanRui06.github.io
   ```

2. **初始化子模块**
   ```bash
   git submodule update --init --recursive
   ```

3. **本地运行**
   ```bash
   hugo server
   ```

4. **访问网站**
   ```
   http://localhost:1313
   ```

## 📝 写作指南

### 创建新文章
```bash
hugo new posts/your-post-title.md
```

### 文章模板
```yaml
---
title: "文章标题"
date: 2025-06-05
draft: false
categories: ["技术"]
tags: ["Hugo", "博客"]
---

文章内容...
```

## 🔧 自定义配置

### 修改个人信息
编辑 `config.yaml` 文件中的以下部分：
```yaml
params:
  author: "你的名字"
  description: "你的博客描述"
  
  socialIcons:
    - name: github
      url: "https://github.com/你的用户名"
```

### 自定义域名
1. 修改 `CNAME` 文件中的域名
2. 在域名服务商处添加 CNAME 记录指向 `username.github.io`

## 🚀 部署说明

网站通过 GitHub Actions 自动部署：
- 推送代码到 `main` 分支自动触发部署
- 自动构建并发布到 GitHub Pages
- 支持自定义域名访问

## 📊 网站统计

- **首页**: 科技风格引导页
- **文章页**: 技术博客文章
- **项目页**: 开源项目展示
- **归档页**: 文章时间线归档
- **关于页**: 个人介绍

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

本项目基于 MIT 许可证开源。

## 🙏 致谢

- [Hugo](https://gohugo.io/) - 快速的静态网站生成器
- [PaperMod](https://github.com/adityatelange/hugo-PaperMod) - 优雅的 Hugo 主题
- [GitHub Pages](https://pages.github.com/) - 免费的静态网站托管

---

**📧 联系我**: [yanrui060127@outlook.com](mailto:yanrui060127@outlook.com)

**🌐 访问网站**: [zephyr-rain.top](https://zephyr-rain.top)