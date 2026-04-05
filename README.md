# AI 精准学习助手 · AI Learning Assistant

> 备考专用 · 纯 HTML · 无需服务器 · 自带 API，用自己的钱学自己的东西  
> Built for exam prep · Pure HTML · No server needed · Bring your own API key

🔗 **在线使用 / Live Demo**: [https://xu105.github.io/ai-learning-assistant/](https://xu105.github.io/ai-learning-assistant/)

---

## 是什么 / What is this

一个跑在浏览器里的 AI 学习助手，基于"精准学、高效学、闭环学"的理念设计，专为备考场景优化。

An AI-powered study assistant that runs entirely in your browser, designed around the principle of precise, efficient, and closed-loop learning — optimized for exam preparation.

**不需要安装任何东西。下载 `index.html`，双击打开，填入 API Key，开始学习。**  
No installation required. Download `index.html`, open it, add your API key, start studying.

---

## 四大学习模式 / Four Study Modes

| 模式 | 说明 |
|------|------|
| 🗺 **学习地图** | 用 80/20 原则生成个性化学习路径，根据你的背景裁剪内容 |
| 💡 **通俗讲解** | 用比喻把复杂概念讲透，支持追问，上下文连续 |
| 📝 **私教刷题** | AI 出题 → 你作答 → AI 批改讲解，考研难度 |
| 🔬 **费曼检验** | 两种模式：小白追问 / 教授面试，倒逼真正理解 |

---

## 支持的 AI 提供商 / Supported Providers

| 提供商 | 国内直连 | 价格 | 推荐理由 |
|--------|----------|------|----------|
| **DeepSeek** | ✅ | 约 ¥1 / 100万 tokens | 最推荐，极省钱，效果好 |
| **智谱 GLM** | ✅ | GLM-4-Flash 免费 | 完全免费，备用首选 |
| **Minimax** | ✅ | 亲民 | 国内稳定 |
| **OpenAI** | ❌ 需VPN | 较贵 | GPT-4o-mini 够用 |
| **自定义** | 取决于服务 | - | 支持任何 OpenAI 兼容接口 |

---

## 快速开始 / Quick Start

**方法一：直接在线用**
打开 [https://xu105.github.io/ai-learning-assistant/](https://xu105.github.io/ai-learning-assistant/)

**方法二：本地使用**
1. 下载 `index.html`
2. 双击用浏览器打开
3. 点击左下角 ⚙️ API 配置
4. 选择提供商，填入 API Key，保存
5. 开始学习

**获取 DeepSeek API Key（推荐）**：
注册 → [platform.deepseek.com](https://platform.deepseek.com/api_keys) → 创建 Key → 粘贴进配置

---

## 隐私说明 / Privacy

- API Key 只保存在**你自己浏览器的 localStorage**，不经过任何第三方服务器
- 所有对话直接从你的浏览器发送到 AI 提供商，中间没有中转
- 刷新页面，对话历史清空，不做任何持久化存储

Your API key is stored only in your browser's localStorage. All requests go directly from your browser to the AI provider. No data passes through any intermediate server.

---

## 适用场景 / Use Cases

- 📚 考研备考（408 计算机基础、数学、英语）
- 🎓 大学课程自学
- 💼 技术面试准备
- 🌱 任何需要高效掌握新知识的场景

---

## 技术栈 / Tech Stack

纯 HTML + CSS + JavaScript，零依赖，零构建，零服务器。  
Pure HTML/CSS/JS. Zero dependencies. Zero build step. Zero server.

---

## License

MIT — 随便用，随便改，随便分享。
