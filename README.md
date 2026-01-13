# 📖 文章内容提取器 / Content Extractor

<p align="center">
  <img src="https://img.shields.io/badge/Chrome-Extension-blue?logo=googlechrome" alt="Chrome Extension">
  <img src="https://img.shields.io/badge/Edge-Add--on-blue?logo=microsoftedge" alt="Edge Add-on">
  <img src="https://img.shields.io/badge/Firefox-Add--on-orange?logo=firefox" alt="Firefox Add-on">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</p>

<p align="center">
  <b>智能提取网页文章和评论，使用 AI 进行分析总结</b><br>
  <i>Extract articles & comments from any webpage, analyze with AI</i>
</p>

---

## ✨ 功能特点 / Features

### 🎯 一键提取 / One-Click Extraction

| 中文 | English |
|------|---------|
| **文章提取** - 自动识别网页正文，提取标题、作者、发布时间等元信息 | **Article Extraction** - Auto-detect main content, extract title, author, publish date |
| **评论提取** - 支持懒加载、分页、虚拟列表等复杂评论区 | **Comment Extraction** - Support lazy-loading, pagination, virtual lists |
| **智能识别** - 对于未适配的网站，使用 AI 自动识别内容区域 | **Smart Detection** - AI-powered content area detection for unsupported sites |

### 🤖 AI 智能分析 / AI Analysis

| 中文 | English |
|------|---------|
| **文章摘要** - 快速了解长文核心内容 | **Article Summary** - Quickly understand long articles |
| **关键要点** - 列出文章的重要信息 | **Key Points** - List important information |
| **观点归纳** - 分类整理评论中的不同观点 | **Opinion Synthesis** - Categorize different viewpoints |
| **情感分析** - 统计评论的情绪分布（正面/负面/中立） | **Sentiment Analysis** - Comment emotion statistics (positive/negative/neutral) |
| **热点识别** - 发现评论中的热门话题 | **Hot Topics** - Discover trending discussions |

### 🌐 广泛支持 / Wide Support

内置适配器，完美支持主流网站 / Built-in adapters for popular websites:

| 平台 / Platform | 支持内容 / Supported Content |
|------|---------|
| 知乎 / Zhihu | 文章、回答、想法 / Articles, answers, thoughts |
| 微博 / Weibo | 博文、评论 / Posts, comments |
| 哔哩哔哩 / Bilibili | 专栏、视频评论 / Columns, video comments |
| 微信公众号 / WeChat | 文章内容 / Article content |
| 小红书 / Xiaohongshu | 笔记、评论 / Notes, comments |
| 贴吧 / Tieba | 帖子、回复 / Threads, replies |
| Twitter/X | 推文、回复 / Tweets, replies |
| YouTube | 视频描述、评论 / Descriptions, comments |
| Medium | 英文文章 / English articles |

### 🤖 多 AI 服务支持 / Multiple AI Services

| 服务商 / Provider | 支持模型 / Supported Models |
|--------|---------|
| OpenAI | GPT-4o, GPT-4, GPT-3.5 |
| Anthropic | Claude 3.5, Claude 3 |
| 智谱 AI / Zhipu AI | GLM-4 (免费额度可用 / Free tier available) |
| Deepseek | Deepseek-V3 |
| 豆包 / Doubao | Doubao 系列 / Doubao series |
| 自定义 / Custom | 任意 OpenAI 兼容 API / Any OpenAI-compatible API |

---

## 📥 安装 / Installation

| 浏览器 / Browser | 安装链接 / Install Link |
|--------|---------|
| Chrome | [Chrome Web Store](#) |
| Edge | [Edge Add-ons](#) |
| Firefox | [Firefox Add-ons](#) |

> 💡 安装后需要在设置中配置 AI 服务的 API 密钥才能使用 AI 分析功能
> 
> 💡 After installation, configure your AI service API key in settings to use AI analysis features

---

## 📸 截图 / Screenshots

<details>
<summary>点击查看截图 / Click to view screenshots</summary>

| 主界面 / Main UI | AI 分析结果 / AI Analysis |
|--------|------------|
| ![主界面](screenshots/main.png) | ![分析结果](screenshots/analysis.png) |

| 文章提取 / Article | 评论提取 / Comments |
|---------|---------|
| ![文章](screenshots/article.png) | ![评论](screenshots/comments.png) |

</details>

---

## 🎨 用户体验 / User Experience

| 中文 | English |
|------|---------|
| 🌓 **深色/浅色主题** - 自动跟随系统设置 | 🌓 **Dark/Light Theme** - Follows system preference |
| 🌍 **多语言支持** - 中文/英文界面，自动检测浏览器语言 | 🌍 **Multi-language** - Chinese/English UI, auto-detected |
| 🎈 **浮动按钮** - 一键快捷操作 | 🎈 **Floating Button** - Quick access |
| ⚡ **后台分析** - 可关闭弹窗继续工作 | ⚡ **Background Analysis** - Work while processing |
| 📋 **右键菜单** - 快捷入口 | 📋 **Context Menu** - Quick shortcuts |

---

## 🔒 隐私保护 / Privacy

我们重视您的隐私 / We value your privacy:

| 中文 | English |
|------|---------|
| ✅ 所有数据仅在本地处理，**不上传至任何服务器** | ✅ All data processed locally, **never uploaded to any server** |
| ✅ 仅在您主动点击时提取内容 | ✅ Content extracted only when you click |
| ✅ API 密钥安全存储在浏览器本地 | ✅ API keys stored securely in browser local storage |
| ✅ 经浏览器商店审核，符合安全规范 | ✅ Reviewed and approved by browser stores |

👉 [查看完整隐私政策 / View Privacy Policy](PRIVACY_POLICY.md)

---

## 📌 使用场景 / Use Cases

| 用户 / User | 场景 (中文) | Use Case (English) |
|------|------|------|
| 🔬 研究人员 / Researchers | 快速收集和分析网络舆情 | Quickly collect and analyze online opinions |
| ✍️ 内容创作者 / Creators | 了解读者反馈和热门话题 | Understand reader feedback and trending topics |
| 📰 新闻阅读者 / Readers | 获取文章摘要，节省阅读时间 | Get article summaries, save reading time |
| 💼 产品经理 / PMs | 分析用户评论，收集产品反馈 | Analyze user comments, collect product feedback |
| 🎓 学生 / Students | 整理学习资料，提取关键信息 | Organize study materials, extract key info |

---

## 📖 使用教程 / How to Use

### 1️⃣ 安装扩展 / Install Extension

从浏览器商店安装扩展后，您会在工具栏看到扩展图标。

After installing from the browser store, you'll see the extension icon in the toolbar.

### 2️⃣ 配置 AI 服务 / Configure AI Service

**中文步骤：**
1. 点击扩展图标，打开侧边栏
2. 点击右上角 ⚙️ 设置按钮
3. 选择 AI 服务提供商（推荐使用智谱 AI，有免费额度）
4. 输入 API 密钥并保存

**English Steps:**
1. Click the extension icon to open the sidebar
2. Click the ⚙️ settings button in the top right
3. Select an AI service provider (Zhipu AI recommended, has free tier)
4. Enter your API key and save

<details>
<summary>💡 如何获取 API 密钥？ / How to get API keys?</summary>

**🆓 推荐免费方案 / Recommended Free Options:**

| 服务商 / Provider | 获取方式 / How to Get | 免费额度 / Free Tier |
|--------|---------|---------|
| 智谱 AI / Zhipu AI | 访问 / Visit [open.bigmodel.cn](https://open.bigmodel.cn) | 新用户赠送免费额度 / Free credits for new users |
| OpenRouter | 访问 / Visit [openrouter.ai](https://openrouter.ai) | 多个免费模型可用 / Multiple free models available |
| Mode.dev | 访问 / Visit [mode.dev](https://mode.dev) | 提供免费模型额度 / Free model credits available |

**💰 付费方案 / Paid Options:**

| 服务商 / Provider | 获取方式 / How to Get |
|--------|---------|
| OpenAI | 访问 / Visit [platform.openai.com](https://platform.openai.com) |
| Deepseek | 访问 / Visit [platform.deepseek.com](https://platform.deepseek.com) |
| Anthropic | 访问 / Visit [console.anthropic.com](https://console.anthropic.com) |

> 💡 **提示 / Tip**：OpenRouter 和 Mode.dev 支持多种模型，使用时选择「自定义」提供商，填入对应的 API 端点即可。
> 
> OpenRouter and Mode.dev support multiple models. Select "Custom" provider and enter the corresponding API endpoint.

</details>

### 3️⃣ 提取内容 / Extract Content

**中文步骤：**
1. 打开任意文章页面（如知乎、微博、公众号等）
2. 点击扩展图标打开侧边栏
3. 点击 **「一键智能分析」** 按钮
4. 等待提取和分析完成

**English Steps:**
1. Open any article page (Zhihu, Weibo, WeChat, etc.)
2. Click the extension icon to open the sidebar
3. Click the **"Smart Analyze"** button
4. Wait for extraction and analysis to complete

### 4️⃣ 查看结果 / View Results

分析完成后，您可以在不同标签页查看 / After analysis, view results in different tabs:

| 标签页 / Tab | 内容 (中文) | Content (English) |
|--------|------|------|
| 📄 文章 / Article | 提取的文章标题、作者、正文内容 | Extracted title, author, main content |
| 💬 评论 / Comments | 提取的评论列表 | Extracted comment list |
| 🤖 分析 / Analysis | AI 生成的摘要、要点、观点分析、情感统计 | AI-generated summary, key points, viewpoints, sentiment |

### 🎈 快捷操作 / Quick Actions

| 中文 | English |
|------|---------|
| **浮动按钮**：在网页右下角会显示浮动按钮，可快速触发提取 | **Floating Button**: Appears at bottom-right of pages for quick access |
| **右键菜单**：在网页上右键可看到扩展的快捷菜单 | **Context Menu**: Right-click on any page to see extension shortcuts |
| **侧边栏**：支持固定在浏览器侧边，边浏览边分析 | **Sidebar**: Can be pinned to browser side, analyze while browsing |

---

## 📝 更新日志 / Changelog

### v1.0.0

| 中文 | English |
|------|---------|
| 🎉 首次发布 | 🎉 Initial release |
| 📄 文章提取：标题、正文、作者、发布时间 | 📄 Article extraction: title, content, author, date |
| 💬 评论提取：懒加载、分页支持 | 💬 Comment extraction: lazy-loading, pagination |
| 🤖 AI 分析：摘要、要点、观点、情感 | 🤖 AI analysis: summary, key points, viewpoints, sentiment |
| 🌐 多网站支持 | 🌐 Multi-website support |
| 🎨 深色/浅色主题 | 🎨 Dark/Light theme |
| 🌍 中文/英文多语言 | 🌍 Chinese/English multi-language |

---

## 📮 反馈 / Feedback

如有问题或建议，欢迎通过以下方式反馈：

If you have questions or suggestions, please provide feedback:

- 🐛 [提交 Issue / Submit Issue](../../issues)
- 💡 [功能建议 / Feature Request](../../issues/new?labels=enhancement)

---

<p align="center">
  <b>让 AI 成为您的阅读助手！</b><br>
  <i>Let AI be your reading assistant!</i>
</p>
