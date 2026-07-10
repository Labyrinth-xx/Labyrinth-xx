<div align="center">

# 四个月，40+ 个项目，5 个至今在生产环境持续运行

**把 AI 当成一支需要制度约束的团队来管——这里的每个项目，都出自同一条「人管 AI 的生产线」。**

*I build with AI the way a factory runs a production line: plan → independent review → gated commits.*
*40+ projects in 4 months · 5 still running in production.*

**[📄 完整作品集 · Full Portfolio](https://claude.ai/code/artifact/3232c539-148d-4966-9ff7-fde8668b405b)**

</div>

---

## 精选项目 · Selected Work

| 项目 | 是什么 | 状态 |
|------|--------|------|
| [**lithe**](https://github.com/Labyrinth-xx/lithe) | 为 AI 时代做的 macOS Markdown 编辑器：人和 AI agent 同时改同一个文件，实时热重载，谁的改动都不丢。Rust + Tauri，23MB，完全离线 | 🚀 已发布 · MIT |
| [**TubeNext**](https://github.com/Labyrinth-xx/TubeNext) | 伦敦地铁通勤助手：iPhone 桌面 / 锁屏小组件直接显示下一班还有几分钟，按时间自动判断去程回程。Swift / SwiftUI + TfL 实时数据 | 🚀 已开源 · MIT |
| [**krypt**](https://github.com/Labyrinth-xx/krypt) | 本地加密密码管理器：Argon2id + AES-256，屏幕永不显示明文，明文不经前端直达剪贴板。Tauri + React + Rust | 🚀 已开源 · MIT |
| [**video-maker**](https://github.com/Labyrinth-xx/video-maker) | 喂一份文字稿，本地渲出带配音和同步字幕的短视频，7 种画风、横竖屏双画幅，全程免费 | 🚀 已开源 · MIT |
| [**ai-chat-relay**](https://github.com/Labyrinth-xx/ai-chat-relay) | BYOK 多模型聊天站：类 claude.ai 前端，API 密钥只存浏览器本地，OAuth + Postgres + Docker 一键部署 | 🚀 已开源 · MIT |
| [**diary-dashboard**](https://github.com/Labyrinth-xx/diary-dashboard) | Obsidian 日记看板插件：打卡连击、热力图、心情曲线、足迹地图，130 项自动化测试 | 🚀 已开源 · MIT |
| [**月薪喵桌宠**](https://github.com/Labyrinth-xx/yuexinmiao-desktop-pet) | 屏幕角落养一只猫：按时段换心情，久坐喝水提醒，Electron 跨平台 | 🚀 已发布 |

> 其余 30+ 个项目涉及个人数据、真实业务或为实验性质，保持私有。完整清单见[作品集](https://claude.ai/code/artifact/3232c539-148d-4966-9ff7-fde8668b405b)。

## 生产环境里还跑着什么

有 5 个服务此刻正在云服务器上 24 小时运行——内容情报流水线（抓取 → 评分 → 人审 → 发布 → 告警全链路）、微信里的 AI 助理、美股异动哨兵等。它们处理真实数据、带告警和回滚，属于「生产在用」而非 demo。细节见[作品集](https://claude.ai/code/artifact/3232c539-148d-4966-9ff7-fde8668b405b)。

## 最特别的一件作品：给 AI 搭的一条生产线

上面所有项目，都是从这套「制度」里生产出来的：

- **规划关** — 动手前必须先产出实现计划，经确认才写代码
- **审查关** — 写代码的 AI 不许审自己的代码，审查交给另一个全新上下文的独立 AI；敏感改动升级为跨模型互审
- **提交关** — 构建、测试、代码检查、密钥扫描全绿才准提交，红了必须修，没有绕过这个选项
- **自学习** — 踩过的坑自动沉淀为可复用的技能，下次直接调用

企业客户最难的从来不是让 AI 能干活，是让 AI **可靠、可审计、可控成本**地干活。这套流程，我先自用了四个月。

---

<div align="center">

*这个主页和上面所有项目一样，也是人和 Claude 一起做出来的。*

</div>
