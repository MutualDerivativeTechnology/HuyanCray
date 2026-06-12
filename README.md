<div align="center">

# HuYanCray

### AI 原生办公与编程平台

**让 AI 成为你的智能协作者**

[![Windows](https://img.shields.io/badge/Windows-10%2B-0078D4?logo=windows&logoColor=white)](#)
[![macOS](https://img.shields.io/badge/macOS-12%2B-000000?logo=apple&logoColor=white)](#)
[![Linux](https://img.shields.io/badge/Linux-Ubuntu%2B-FCC624?logo=linux&logoColor=black)](#)
[![Version](https://img.shields.io/badge/Version-0.1.0-7C6FFF?labelColor=2D2A4A)](#)

[下载安装](#-下载安装) · [功能介绍](#-功能介绍) · [使用指南](#-使用指南) · [常见问题](#-常见问题)

</div>

---

## 为什么选择 HuYanCray？

传统的 AI 工具是"你问它答"的单轮对话。HuYanCray 不同——它是**原生为 AI Agent 设计**的协作环境：

- **不只是补全代码** — 多智能体团队协作，Researcher 调研、Coder 编码、Reviewer 审查，自动分工
- **不只是聊天** — 30+ 企业连接器，飞书/钉钉/腾讯文档/Notion/GitHub，AI 直接操作你的工作流
- **不只是工具** — 记忆系统让 AI 跨会话保持上下文，技能系统让工作流可复用、可分享

---

## 功能介绍

### 🤖 智能编程

| 能力 | 说明 |
|------|------|
| **多模型自由切换** | Claude / OpenAI / DeepSeek / Qwen / AWS Bedrock / 本地 Ollama，一键切换无需改配置 |
| **Code-Simplifier** | 65 条代码简化规则自动识别，让 AI 写出更干净的代码 |
| **Plan 模式** | 重大变更先规划再执行，每一步都需要你确认 |
| **Design-to-Code** | 设计稿直接生成生产级代码 |
| **Vim 模式** | 完整的 Vim 键绑定，终端党的效率首选 |
| **语音输入** | 本地 Whisper 识别，口述需求直接变成代码 |

### 👥 多智能体协作

| 角色 | 职责 |
|------|------|
| **Leader** | 任务拆解与分配 |
| **Researcher** | 信息搜集与调研 |
| **Coder** | 代码编写与实现 |
| **Reviewer** | 代码审查与优化 |
| **Tester** | 测试用例编写 |
| **Designer** | UI/UX 设计实现 |
| **Writer** | 文档撰写 |
| **Coordinator** | 多 Agent 协调调度 |

多个 Agent 自动组建团队、并行工作、消息通信，结果自动汇总。

### 🔌 连接器生态

HuYanCray 通过连接器直接操作你的工作平台，AI 不再是信息孤岛：

| 类别 | 连接器 |
|------|--------|
| **文档协作** | 腾讯文档、金山文档、Notion、乐享知识库、iWiki |
| **即时通讯** | 飞书、钉钉、企业微信、QQ 邮箱、网易邮箱 |
| **项目管理** | TAPD、Jira、GitHub |
| **数据服务** | 天眼查、企查查、北大法宝、通达信、东方财富 |
| **云服务** | 腾讯云 CloudBase、百度网盘、微云 |
| **其他** | 腾讯问卷、腾讯会议、销售易 CRM、智研 CICD |

### 🧠 记忆与技能

- **持久化记忆** — AI 记住你的项目偏好、编码风格、历史决策，跨会话保持上下文
- **技能系统** — 可复用工作流，SKILL.md 定义，一键安装社区技能
- **自动化引擎** — 定时任务、事件触发、审批流，让 AI 7×24 小时待命

---

## 📦 下载安装

### 系统要求

| 平台 | 最低版本 | 架构 |
|------|----------|------|
| Windows | 10 1809+ | x64 |
| macOS | 12 Monterey+ | x64 / Apple Silicon |
| Linux | Ubuntu 20.04+ | x64 |

### 下载

前往 [Releases](../../releases) 页面下载最新版本：

| 文件 | 说明 |
|------|------|
| `HuYanCray-Setup-x.x.x.exe` | Windows 安装程序（推荐） |
| `HuYanCray-x.x.x-win.zip` | Windows 便携版（免安装） |
| `HuYanCray-x.x.x-mac.dmg` | macOS DMG 镜像 |
| `HuYanCray-x.x.x-mac.zip` | macOS ZIP 包 |
| `HuYanCray-x.x.x-linux.AppImage` | Linux AppImage（免安装） |

### 安装步骤

#### Windows

1. 下载 `HuYanCray-Setup-x.x.x.exe`
2. 双击运行，按提示完成安装
3. 首次启动需要配置 AI 模型 API Key

> 💡 便携版用户：解压 ZIP 后运行 `HuYanCray.exe`，无需安装

#### macOS

1. 下载 `HuYanCray-x.x.x-mac.dmg`
2. 双击打开，将 HuYanCray 拖入 Applications 文件夹
3. 首次打开如提示"无法验证"，前往 系统设置 → 隐私与安全性 → 仍要打开

#### Linux

```bash
# AppImage 方式（推荐）
chmod +x HuYanCray-x.x.x-linux.AppImage
./HuYanCray-x.x.x-linux.AppImage

# deb 方式
sudo dpkg -i huyancray_x.x.x_amd64.deb

# rpm 方式
sudo rpm -i huyancray-x.x.x.x86_64.rpm
```

---

## 🚀 使用指南

### 1. 配置 AI 模型

首次启动后，进入 **设置 → AI 模型**：

- **在线模型**：填入 API Key（支持 Claude / OpenAI / DeepSeek / Qwen 等）
- **本地模型**：安装 [Ollama](https://ollama.com)，拉取模型后自动识别

### 2. 开始对话

直接在对话框中输入你的需求：

```
帮我用 React 写一个登录页面，要求支持手机号和邮箱两种登录方式
```

### 3. 使用斜杠命令

输入 `/` 触发命令菜单：

| 命令 | 用途 |
|------|------|
| `/commit` | 智能生成 Git Commit |
| `/review` | 代码审查 |
| `/compact` | 压缩上下文（长对话时节省 Token） |
| `/doctor` | 环境诊断 |
| `/memory` | 管理持久化记忆 |
| `/skills` | 技能管理 |
| `/cost` | 查看 Token 使用成本 |

### 4. 多智能体模式

复杂任务可以使用团队模式：

```
/teams — 创建 Agent 团队，自动分工协作
```

Leader 自动拆解任务 → 分配给 Researcher/Coder/Reviewer → 结果汇总

### 5. 安装技能

```
/skills install — 从技能市场安装社区技能
```

技能是可复用的自动化工作流，覆盖前端开发、数据分析、文档写作等场景。

### 6. 连接企业平台

进入 **设置 → 连接器**，授权你使用的办公平台。连接后，AI 可以直接读取文档、发送消息、管理任务。

---

## 🔒 安全与隐私

| 机制 | 说明 |
|------|------|
| **本地优先** | 代码在本地执行，不上传到云端 |
| **API Key 本地存储** | 密钥存储在本地 Keychain/Credential Manager，不外传 |
| **危险操作确认** | 删除文件、推送代码等操作需要你确认 |
| **本地模型支持** | 通过 Ollama 运行本地模型，数据不出本机 |
| **代码混淆分发** | 生产构建采用代码混淆，保护商业逻辑 |

---

## ❓ 常见问题

### 支持哪些 AI 模型？

HuYanCray 支持国内外主流大模型：Claude、OpenAI GPT、DeepSeek、Qwen、AWS Bedrock 等。同时支持通过 Ollama 运行本地模型（Llama、Qwen、DeepSeek R1 等），无需联网。

### 是否需要联网？

- 使用在线模型（Claude/OpenAI 等）需要联网
- 使用 Ollama 本地模型可完全离线运行
- 连接器功能（飞书/钉钉等）需要联网

### Token 费用如何计算？

HuYanCray 本身不收取 AI 调用费用。Token 费用由你选择的 AI 模型提供商收取。你可以在设置中配置预算上限，并使用 `/cost` 随时查看消耗。

### 数据存在哪里？

所有数据（对话历史、项目配置、API Key）存储在你本地设备上，不会上传到 HuYanCray 服务器。

### Windows 安装时提示"已阻止此应用"？

右键安装程序 → 属性 → 勾选"解除锁定" → 重新运行。

---

## 🗺️ 产品路线图

| 阶段 | 重点 | 状态 |
|------|------|------|
| **Now** | 桌面客户端核心功能、多模型支持、连接器生态 | ✅ 已发布 |
| **Next** | 团队协作空间、技能市场、自动化工作流引擎 | 🚧 进行中 |
| **Later** | 移动端适配、企业私有化部署、插件 SDK | 📋 规划中 |

---

## 📄 许可证

本软件为专有软件，保留所有权利。使用前请阅读 [LICENSE](./LICENSE)。

---

<div align="center">

**HuYanCray Team · 2026**

[报告问题](../../issues) · [功能建议](../../issues/new) · [加入社区]()

</div>
