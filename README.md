# GetModels

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/YangguangZhou/GetModels?style=flat-square)](https://github.com/YangguangZhou/GetModels/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/YangguangZhou/GetModels?style=flat-square)](https://github.com/YangguangZhou/GetModels/network/members)
[![GitHub issues](https://img.shields.io/github/issues/YangguangZhou/GetModels?style=flat-square)](https://github.com/YangguangZhou/GetModels/issues)
[![Vercel](https://img.shields.io/badge/Vercel-部署-black?style=flat-square&logo=vercel)](https://vercel.com/new/git/external?repository-url=https://github.com/YangguangZhou/GetModels)

✨ 轻松获取 OpenAI 格式 API 的可用模型列表 ✨

[演示](https://models.jerryz.com.cn/) | [报告问题](https://github.com/YangguangZhou/GetModels/issues/new)

</div>

## 📑 目录

- [功能特点](#-功能特点)
- [在线体验](#-在线体验)
- [本地运行](#-本地运行)
- [Vercel 部署](#-vercel-部署)
- [使用指南](#-使用指南)
- [常见问题](#-常见问题)

## 🚀 功能特点

- 🔍 **模型查询** - 查询不同 API 提供商的可用模型
- 🧩 **模型过滤** - 按类型筛选模型（聊天模型、嵌入模型等）
- 🎨 **Material You 设计** - 现代化界面设计，支持亮色/暗色模式
- 🌐 **兼容多种提供商** - 支持 OpenAI 及其兼容 API 格式的其他提供商
- 📱 **响应式布局** - 在各种设备上都有良好的显示效果

## 🌈 在线体验

访问 [https://models.jerryz.com.cn/](https://models.jerryz.com.cn/) 可以直接体验 GetModels。

## 💻 本地运行

GetModels 是一个纯静态网站，无需后端服务，可以轻松在本地运行：

1. 克隆仓库：

```bash
git clone https://github.com/YangguangZhou/GetModels.git
cd GetModels
```

2. 使用您喜欢的方式启动一个静态服务器：

使用 Python:
```bash
# Python 3
python -m http.server 3000
# Python 2
python -m SimpleHTTPServer 3000
```

使用 Node.js:
```bash
# 使用 npx
npx serve

# 或安装全局 serve 包
npm install -g serve
serve
```

3. 打开浏览器，访问 `http://localhost:3000` 即可使用

## 🚢 Vercel 部署

点击下面的按钮，一键部署到 Vercel：

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/YangguangZhou/GetModels)

### 手动部署步骤：

1. Fork 这个仓库
2. 注册/登录 [Vercel](https://vercel.com/)
3. 在 Vercel 点击 "New Project"
4. 选择您的 GetModels 仓库
5. 使用默认设置，点击 "Deploy"

## 📖 使用指南

1. **配置 API 信息**
   - 输入 API 基础 URL（例如：`https://api.openai.com/v1` ）
   - 输入您的 API 密钥
   - 选择您想查询的模型类型（所有模型、嵌入模型、对话模型）

2. **查询模型**
   - 点击"查询模型"按钮
   - 系统将显示符合条件的所有模型列表

3. **查看结果**
   - 查看模型 ID 和提供者信息
   - 可以点击"清空结果"重新开始

## ❓ 常见问题

### 为什么我看不到模型列表？

请检查：
- API 密钥是否正确
- API 基础 URL 是否正确
- 网络连接是否正常
- API 提供商是否支持 /models 端点

### 我的 API 密钥安全吗？

是的。您的 API 密钥仅存储在您的浏览器中，不会发送到除您指定的 API 提供商以外的任何服务器。所有请求都直接从您的浏览器发出。

### 为什么有些模型不显示？

不同的 API 提供商可能有不同的模型命名规则。模型类型筛选是基于常见的命名模式实现的，如果有特殊命名的模型可能会被错误分类。

---

<div align="center">
  由 ❤️ 和 ☕ 驱动 | 
  <a href="https://github.com/YangguangZhou">YangguangZhou</a> © 2025
</div>