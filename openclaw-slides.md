# 🦞 OpenClaw — 互联网技术中心内部分享

> **互联网技术中心内部分享 · 2026.03.10**
>
> ⭐ 279k Stars · 👥 1,100 Contributors · 📜 MIT License · 🏷️ v2026.3.7

---

## OpenClaw 是什么？

> **"运行在本地，可以通过飞书/微信等远程指挥，7×24 自动运转的 AI 助手"**

### 🏆 GitHub 全站 Star #1

![Star History](https://api.star-history.com/svg?repos=openclaw/openclaw&type=Date&theme=dark)

| 指标 | 数据 | 指标 | 数据 |
|------|------|------|------|
| ⭐ Stars | **279k** | 🍴 Forks | **53.1k** |
| 👥 Contributors | **1,100** | 📝 Commits | **17k** |
| 🐛 Issues | **15.6k** | 🔀 PRs | **22k** |

`MIT 开源` · `自托管` · `22+ 渠道` · `真 Agent`

---

## 🏗️ Architecture：核心架构

![龙虾系统架构](openclaw-arch-v2.png)

---

## 为什么爆火？

> *龙虾不是工具，是有记忆、有经验、能持续成长的数字员工*

- 🔓 **开源 + 本地部署** — 数据隐私可控，不被厂商锁定
- 📚 **Skill 生态** — 内置 + 自定义 + 第三方，无限扩展
- 🧠 **Memory 系统** — 跨会话记忆，越用越懂你
- ⚡ **7×24 自动化运转** — 自动执行任务，像数字员工一样持续工作
- 💬 **多渠道整合** — 飞书/Discord/Telegram 一个入口全覆盖
- 🤖 **多模型自由切换** — OpenAI / Claude / 国内 / 本地模型
- 📱 **设备配对** — 连手机、IoT，远程控制能力
- 🦞 **"养龙虾"梗** — 降低传播门槛，社交属性强

![龙虾 vs 普通 Agent](claw-vs-agent.jpg)

---

## 🖥️ 运行环境：一台完整的电脑

> **从"沙箱里的对话框"进化为"拥有完整权限的数字员工"**

![环境](env-computer-v2.png)

- **完整系统权限** — Shell、文件、网络全打通，坐在电脑前能干的事它全能干
- **浏览器自动化** — 像真人一样操作网页，搜索、填表、截图一气呵成
- **软件协同** — 邮件、Office、API 调用全打通，串联日常工作流
- **低配即可** — 不需要高端显卡，普通老电脑就能当 AI 工位

---

## 🧠 Memory：越用越懂你

> **LLM 说"我记住了"只是幻觉，OpenClaw 用文件系统构建真实记忆**

![记忆系统](memory-simple.png)

- **混合检索** — 语义向量 + 关键词混合检索，找回记忆更精准
- **记忆文件** — 每日记录（memory/YYYY-MM-DD.md）与核心事实（MEMORY.md）存储，永久保留工作经验
- **自动冲刷 (Auto Flush)** — 会话即将写满时，自动将重要事实存入本地文件
- **SQLite-vec 加速** — 本地高性能向量引擎，毫秒级召回万条记忆碎片

---

## 📚 Skill：无限拓展能力

> **无需复杂编码，通过 Markdown 文件即可赋予 Agent 全新能力**

![技能](skills-evolution.png)

- **SKILL.md** — 技能的核心定义，只需描述"做什么"和"怎么做"
- **极简扩展** — 在 `/skills` 下新建文件夹并放入文档，AI 即可瞬间习得
- **ClawHub 生态** — 官方与社区技能一键安装，实现全球技能秒级同步
- **私有与共享** — 支持工作区专用技能或系统级全局共享，灵活配置
- **自我进化** — 解决问题后自动反思并生成 Skill，永久避免重复踩坑

---

## ⚡ 自动化：7×24 不间断

> **不会累、不会情绪化、不会因为放假就消失**

![自动化](automation-logic.png)

- **Cron 定时任务** — 定时提醒、定时执行
- **主动监控** — 主动监控相关事件，自动处理，提供报告
- **Webhook 触发** — GitLab/邮件/日历等外部事件自动响应

---

## 💬 Channels：多渠道整合

> **你在哪里，龙虾就在哪里。支持 20+ 主流消息平台。**

![多渠道整合](channels-hub.png)

### 常用渠道

- **Feishu** (飞书)
- **Discord**
- **Telegram**
- **Slack**
- **WhatsApp**
- **WeChat** (微信)
- **Teams**
- **WebChat**

---

## 使用场景：打造你的 7×24 数字员工

![使用场景](use-cases-whiteboard.png)

### 💼 智能协作与业务

| 场景 | 说明 |
|------|------|
| **飞书数字员工** | 进驻群聊直接对话，查阅文档、总结会议、管理团队日程 |
| **用户原声中心** | 监控全渠道售后与差评，自动聚类总结并推送至相关负责人 |
| **内部技能市场** | 技术中心能力沉淀，实现 Agent 技能的发现、共享与复用 |

### 🛠️ 研发与运维守护

| 场景 | 说明 |
|------|------|
| **远程指挥编码** | 随时随地通过即时通讯终端下达指令，自动化处理代码重构 |
| **质量与 Bug 巡查** | 全天候自动巡检系统 Bug，监控线上服务状态与安全风险 |
| **运维线上巡检** | 定时执行资源检查，实时推送告警并提供初步诊断建议 |

---

## 快速上手

```bash
# 前置条件：Node.js ≥ 22
$ node --version

# 安装 (macOS / Linux)
$ curl -fsSL https://openclaw.ai/install.sh | bash

# 安装 (Windows PowerShell)
# iwr -useb https://openclaw.ai/install.ps1 | iex

# 引导式配置（推荐）
$ openclaw onboard --install-daemon

# 检查 Gateway 状态
$ openclaw gateway status

# 打开控制面板
$ openclaw dashboard
```

> 📖 文档：[docs.openclaw.ai](https://docs.openclaw.ai)
> 💻 源码：[github.com/openclaw/openclaw](https://github.com/openclaw/openclaw)

---

## Thank You 🦞

```bash
$ open https://github.com/openclaw/openclaw
$ open https://docs.openclaw.ai
```

`github.com/openclaw` · `docs.openclaw.ai` · `discord.gg/clawd`

> 互联网技术中心内部分享 · 2026.03.10 · Q&A
