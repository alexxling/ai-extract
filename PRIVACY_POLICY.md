# 隐私政策 / Privacy Policy

**文章内容提取器 (Content Extractor)**

最后更新 / Last Updated: 2024年12月 / December 2024

> 🌐 本扩展支持中文和英文界面，会根据您的浏览器语言自动设置
> 
> 🌐 This extension supports Chinese and English interface, automatically set based on your browser language

---

## 中文版

### 概述

"文章内容提取器"（以下简称"本扩展"）尊重并保护用户隐私。本隐私政策说明我们如何收集、使用和保护您的信息。

### 数据收集

本扩展在用户**主动点击提取按钮时**，会读取当前网页的以下内容：

- 文章标题、正文内容、作者信息、发布时间。
- 评论区内容（包括评论者昵称、评论内容、点赞数等公开信息）
- 页面 URL 和元数据

**重要说明**：
- 本扩展**不会自动收集**任何数据
- 本扩展**不会在后台运行**时收集数据
- 所有数据提取操作都需要用户明确触发

### 数据使用

提取的内容仅用于以下目的：

1. **本地展示**：在扩展弹窗中显示提取的文章和评论内容
2. **AI 分析**（可选）：如果用户配置了 AI 服务，内容将发送至用户选择的 AI 服务进行分析

### 数据存储

- 提取的内容仅**临时存储**在浏览器本地会话中
- 用户配置（如 API 密钥、界面语言偏好）存储在浏览器本地存储中
- **我们不运营任何服务器**，不会将您的数据传输到我们的服务器
- 关闭标签页后，提取的内容会自动清除
- 语言设置会被保存，以便下次打开时使用您偏好的语言

### 第三方服务

如果用户选择使用 AI 分析功能，提取的内容将发送至用户配置的第三方 AI 服务。支持的服务包括：

| 服务提供商 | API 地址 | 隐私政策链接 |
|-----------|----------|-------------|
| OpenAI | api.openai.com | https://openai.com/privacy |
| Anthropic Claude | api.anthropic.com | https://www.anthropic.com/privacy |
| 智谱 AI | open.bigmodel.cn | https://open.bigmodel.cn/dev/howuse/privacypolicy |
| Deepseek | api.deepseek.com | https://www.deepseek.com/privacy |
| 豆包（字节跳动） | ark.cn-beijing.volces.com | https://www.volcengine.com/docs/privacy |

**用户需自行了解并同意相应第三方服务的隐私政策。**

### 权限说明

本扩展请求以下浏览器权限：

| 权限 | 用途说明 |
|------|---------|
| `activeTab` | 仅在用户点击扩展图标时，访问当前标签页内容 |
| `storage` | 存储用户配置（如 AI API 密钥），仅限浏览器本地存储 |
| `scripting` | 在网页中执行内容提取脚本 |
| `alarms` | 后台任务调度，确保长时间 AI 分析不中断 |
| `contextMenus` | 提供右键菜单快捷操作 |
| `host_permissions (<all_urls>)` | 允许在任意网页上提取文章和评论内容 |

### 我们不会做的事情

- ❌ 收集您的个人身份信息
- ❌ 追踪您的浏览历史
- ❌ 向第三方出售或分享您的数据
- ❌ 在您不知情的情况下收集数据
- ❌ 将数据存储在我们的服务器上

### 数据安全

- API 密钥使用浏览器的安全存储机制保存
- 所有与第三方 AI 服务的通信均使用 HTTPS 加密
- 扩展经过浏览器商店审核，符合安全规范

### 儿童隐私

本扩展不针对 13 岁以下的儿童，我们不会故意收集儿童的个人信息。

### 隐私政策更新

我们可能会不时更新本隐私政策。更新后的政策将在此页面发布，并更新"最后更新"日期。

### 联系我们

如果您对本隐私政策有任何疑问，请通过以下方式联系我们：

- GitHub Issues: [项目地址]
- 邮箱: [您的邮箱地址]

---

## English Version

### Overview

"Content Extractor" (hereinafter referred to as "the Extension") respects and protects user privacy. This Privacy Policy explains how we collect, use, and protect your information.

### Data Collection

The Extension reads the following content from the current webpage **only when the user actively clicks the extract button**:

- Article title, body content, author information, publication time
- Comment section content (including commenter nicknames, comment content, likes, and other public information)
- Page URL and metadata

**Important Notes**:
- The Extension **does NOT automatically collect** any data
- The Extension **does NOT collect data** when running in the background
- All data extraction operations require explicit user action

### Data Usage

Extracted content is used only for the following purposes:

1. **Local Display**: Showing extracted articles and comments in the extension popup
2. **AI Analysis** (optional): If the user has configured an AI service, content will be sent to the user-selected AI service for analysis

### Data Storage

- Extracted content is only **temporarily stored** in the browser's local session
- User configurations (such as API keys, interface language preference) are stored in browser local storage
- **We do not operate any servers** and will not transmit your data to our servers
- Extracted content is automatically cleared when the tab is closed
- Language settings are saved so that your preferred language is used next time

### Third-Party Services

If users choose to use the AI analysis feature, extracted content will be sent to the third-party AI service configured by the user. Supported services include:

| Service Provider | API Endpoint | Privacy Policy |
|-----------------|--------------|----------------|
| OpenAI | api.openai.com | https://openai.com/privacy |
| Anthropic Claude | api.anthropic.com | https://www.anthropic.com/privacy |
| Zhipu AI | open.bigmodel.cn | https://open.bigmodel.cn/dev/howuse/privacypolicy |
| Deepseek | api.deepseek.com | https://www.deepseek.com/privacy |
| Doubao (ByteDance) | ark.cn-beijing.volces.com | https://www.volcengine.com/docs/privacy |

**Users should review and agree to the privacy policies of the respective third-party services.**

### Permission Explanations

The Extension requests the following browser permissions:

| Permission | Purpose |
|------------|---------|
| `activeTab` | Access current tab content only when user clicks the extension icon |
| `storage` | Store user configurations (such as AI API keys), browser local storage only |
| `scripting` | Execute content extraction scripts on web pages |
| `alarms` | Background task scheduling to ensure long AI analysis tasks are not interrupted |
| `contextMenus` | Provide right-click menu shortcuts |
| `host_permissions (<all_urls>)` | Allow extraction of articles and comments on any webpage |

### What We Do NOT Do

- ❌ Collect your personal identity information
- ❌ Track your browsing history
- ❌ Sell or share your data with third parties
- ❌ Collect data without your knowledge
- ❌ Store data on our servers

### Data Security

- API keys are saved using the browser's secure storage mechanism
- All communications with third-party AI services use HTTPS encryption
- The extension has been reviewed and approved by browser stores, meeting security standards

### Children's Privacy

The Extension is not intended for children under 13 years of age, and we do not knowingly collect personal information from children.

### Privacy Policy Updates

We may update this Privacy Policy from time to time. Updated policies will be posted on this page with an updated "Last Updated" date.

### Contact Us

If you have any questions about this Privacy Policy, please contact us through:

- GitHub Issues: [Project URL]
- Email: [Your Email Address]

---

© 2024 文章内容提取器 / Content Extractor. All rights reserved.
