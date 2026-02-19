# 🌌 SillyTavern V3 卡片构建器 (Ultimate Card Builder)

![Astro](https:
![Vanilla JS](https:
![License](https:

这是一个角色卡构建平台
结合了语言模型接口、世界书，管理、正则 UI 注入以半流水线的方式打造角色卡。

## ✨ 核心特性 (Features)

### 🤖 双重 AI 智能流水线
- **预设提取**：支持直接导入酒馆原生 `.json` 预设，自动提取底层逻辑与文风，约束 AI 的生成方向。
- **上下文防漂移**：在自动生成世界书（Worldbook）时，底层引擎会自动捕获已存在的设定，采用“链式迭代生成”
- **定点重写**：对单条世界书不满意？输入你的定向要求，AI 将精准锁定该条目进行局部覆盖重写。

### 📖 世界书控制 (Worldbook CRUD)
- 告别繁琐的酒馆内编辑，支持在卡片创建期就注入强大的规则。
- 完整支持 V3 规范下的高阶参数：`Strategy (触发策略)`、`Depth (挂载深度)`、`Order (插入顺序)`、`Role (系统/用户/AI)` 及 `Probability (触发概率)`。

### 📊 动态状态栏一键注入 (Status Bar Injection)
- **半 AI 构思**：只需输入角色描述，AI 会自动为你构思出极具沉浸感的监控字段（如赛博朋克风的“义体完整度、污染指数”）。
- **零代码正则注入**：一键生成并在底层卡片中写入 `regex_scripts`。导入酒馆后，AI 每次回复都会自动在末尾渲染带有赛博发光 CSS UI 的状态面板！
- **本地草稿箱**：所有进度实时静默保存至浏览器的 `localStorage`

## 🚀 快速开始 (Getting Started)

本项目基于 [Astro](https:

### 1. 环境准备
确保你的电脑上安装了 Node.js (推荐 v18+)。

### 2. 克隆与安装
```bash
git clone [https:
cd 你的仓库名
npm install

测试请使用npm run dev
生产环境请使用npm run build
