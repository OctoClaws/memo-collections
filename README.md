# 📌 Memo Collections

> 好记性不如 Memo —— AI 驱动的个人知识收藏库

## 这是什么？

这是一个由 AI Agent（[Memo](https://github.com/openclaw/openclaw)）自动维护的知识收藏库。

你只需要发一条链接，Memo 会自动：
- 🔍 **识别内容** — 抓取标题、描述、关键信息
- 🗂 **分类归档** — 按用途/场景自动判断方向
- 🏷 **打标签** — 多维度标签，确保能被找到
- 📝 **写摘要** — 一句话说清楚是什么、为什么值得记
- 🔗 **交叉关联** — Obsidian 双链，知识不是孤岛
- 📊 **编译 Wiki** — 定期综合分析，提炼趋势洞察

## 架构

```
collections/
├── {方向}/
│   ├── entries/        # 📥 原始收藏（JSON + Markdown）
│   └── wiki/           # 🧠 知识编译层（AI 维护）
│       ├── overview.md # 方向综合概览 + 趋势观察
│       └── {实体}.md   # 关键概念深度页
├── _index.json         # 全量索引
├── _wiki-index.md      # Wiki 全局索引 + 跨方向关联
└── _log.md             # 操作日志
```

## 当前方向

| 方向 | 说明 | 条目数 |
|------|------|--------|
| 🎬 `video-creation` | AI 视频生成与创作 | 7 |
| 🦞 `openclaw` | OpenClaw 部署/配置/生态 | 5 |
| 🤖 `agent-ecosystem` | AI Agent 工具链与框架 | 4 |
| 🎭 `live2d-creation` | Live2D 创作工具与工作流 | 3 |
| 🔬 `ai-research` | AI/ML 研究与技术 | 2 |
| 🍎 `macos-apps` | macOS 应用推荐 | 2 |
| 🛠 `project-dev` | 项目开发工具与流程 | 2 |
| 💼 `job-hunting` | 找工作/简历 | 1 |
| 📚 `learning` | 学习资源与教程 | 1 |
| 💰 `making-money` | 搞钱/副业/商业模式 | 1 |
| ⚡ `productivity` | 效率工具与工作流 | 1 |

> 方向不是固定的，随兴趣动态扩展。

## 灵感来源

受 [Karpathy 的 LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) 启发 —— 不做被动 RAG 检索，而是让 AI 主动构建持久化知识库，知识越积越厚。

**关键区别：**
- 传统 RAG：每次从零检索 → 拼答案 → 什么都没沉淀
- Memo Collections：收藏即编译 → 交叉引用 → 趋势洞察 → 知识复利

## 如何使用

### 🔍 用 Obsidian 可视化浏览

1. 下载 [Obsidian](https://obsidian.md)（免费）
2. Clone 本仓库
3. 用 Obsidian 打开 `collections` 文件夹
4. 按 `Ctrl+G` 查看知识图谱

所有条目都使用 `[[双链]]` 互相关联，图谱视图一目了然。

### 🤖 搭建你自己的 Memo

本项目基于 [OpenClaw](https://github.com/openclaw/openclaw) 构建。你可以：

1. 安装 OpenClaw
2. 创建一个 Agent，参考本仓库的 SOUL.md 设定角色
3. 连接 Telegram / Discord / Signal 等消息渠道
4. 发链接给你的 Memo，它会自动收藏和整理

## 设计哲学

- **沉默高效** — 存好、归类、打标签、回一句确认，不废话
- **按用途分类** — 看「拿来干什么」，不看「底层用了什么技术」
- **检索即正义** — 存的唯一目的是为了找到
- **不丢东西** — 存入的内容永远不删，除非明确要求

## License

本仓库内容为个人知识收藏，仅供参考和学习。

---

_📌 Memo — 你负责发现，我负责永远不丢。_
