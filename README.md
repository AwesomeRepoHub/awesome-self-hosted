<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>自部署应用精选</h1>
<p>把自己的数据拿回来：相册、网盘、影音、自动化和部署面板，附资源占用与上手难度</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-self-hosted?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-self-hosted?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-self-hosted?style=flat-square&color=8250df"></p>

<p><a href="README.en.md">English</a> · <a href="CONTRIBUTING.md">参与贡献</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">全部合集</a></p>
</div>

> **31 个项目，共 2.1M Stars。** Stars、许可证、最近提交时间由 GitHub API 实时读取，数据更新于 2026-10-24。排名按 Stars 排序，仅作热度参考，不代表质量。

<sub>读表说明：Stars 与「更新」都是生成时从 GitHub API 读到的真实值；许可证取自仓库；括号里是使用前要知道的限制。</sub>

## 30 秒选型

| 你的情况 | 从这里开始 |
|:--|:--|
| 换掉 iCloud / Google 相册 | [Immich](https://github.com/immich-app/immich) — 手机自动备份、人脸与地点检索都有，界面几乎无缝迁移 |
| 自建网盘加在线文档 | [Nextcloud](https://github.com/nextcloud/server) — 文件、日历、通讯录、在线 Office 一套齐，客户端全平台 |
| 把部署这件事自动化 | [Coolify](https://github.com/coollabsio/coolify) — Git 推送即部署，证书、备份、数据库都帮你管 |
| 家里的服务挂了一秒知道 | [Uptime Kuma](https://github.com/louislam/uptime-kuma) — 监控站点和端口，异常直接推 Telegram 或邮件 |

## 目录

- [相册、影音与文档](#相册影音与文档)
- [协作与知识](#协作与知识)
- [自动化与日常工具](#自动化与日常工具)
- [部署、接入与远程](#部署接入与远程)

## 相册、影音与文档

_占用硬盘最多的一类，装之前先算容量。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [Immich](https://github.com/immich-app/immich) | 自建相册，手机自动备份、人脸与地点检索，体验接近 iCloud | 117k | `AGPL-3.0` | 2026-10 |
| [Jellyfin](https://github.com/jellyfin/jellyfin) | 自建影音库，海报墙、转码、多端播放，替代 Plex 免费方案 | 58.5k | `GPL-2.0` | 2026-10 |
| [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | 扫描件 OCR 归档，按标签、日期检索合同发票 | 47.0k | `GPL-3.0` | 2026-10 |
| [PhotoPrism](https://github.com/photoprism/photoprism) | 基于 AI 的图片管理，按人物和场景自动归类，适合整理老照片 | 40.3k | `自定义` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 协作与知识

_多人一起用才值得部署的一类。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [NocoDB](https://github.com/nocodb/nocodb) | Airtable 开源替代，把表格直接变成数据库和 API | 65.3k | `自定义` | 2026-10 |
| [Memos](https://github.com/usememos/memos) | 极简自托管备忘录，像发微博一样记想法，Markdown 存储 | 64.0k | `MIT` | 2026-10 |
| [Gitea](https://github.com/go-gitea/gitea) | 轻量 Git 服务，几百 MB 内存就能跑，适合内网代码托管 | 58.7k | `MIT` | 2026-10 |
| [Mastodon](https://github.com/mastodon/mastodon) | 去中心化微博，自建实例可与其他实例互通 | 50.4k | `AGPL-3.0` | 2026-10 |
| [Gogs](https://github.com/gogs/gogs) | 单二进制就能跑的 Git 服务，比 Gitea 更轻 | 47.9k | `MIT` | 2026-10 |
| [Trilium](https://github.com/TriliumNext/Trilium) | 层级笔记加关系图，适合长期个人知识库 | 38.5k | `AGPL-3.0` | 2026-10 |
| [Khoj](https://github.com/khoj-ai/khoj) | 自托管 AI 第二大脑，直接问自己的文档和网页 | 37.8k | `AGPL-3.0` | 2026-08 |
| [Nextcloud](https://github.com/nextcloud/server) | 自建网盘与在线 Office，文件、日历、通讯录一套齐 | 37.3k | `AGPL-3.0` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 自动化与日常工具

_装完立刻能感觉到效率提升的一组。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [n8n](https://github.com/n8n-io/n8n) | 节点式自动化，接 400+ 服务，AI 工作流也能编排 | 208k | `自定义` | 2026-10 |
| [Dify](https://github.com/langgenius/dify) | 可视化编排 agent 工作流与 RAG，多模型接入 | 159k | `自定义` | 2026-10 |
| [Open WebUI](https://github.com/open-webui/open-webui) | 给本地模型套一个 ChatGPT 式界面，支持多用户与知识库 | 157k | `自定义` | 2026-10 |
| [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) | 浏览器里合并、拆分、OCR、加水印，PDF 工具箱 | 94.8k | `自定义` | 2026-10 |
| [Uptime Kuma](https://github.com/louislam/uptime-kuma) | 监控站点和端口，挂了发 Telegram 或邮件告警 | 92.8k | `MIT` | 2026-10 |
| [Unsloth](https://github.com/unslothai/unsloth) | 本地跑与微调大模型的界面，支持 GGUF、MLX | 78.5k | `Apache-2.0` | 2026-10 |
| [LibreChat](https://github.com/LibreChat-AI/LibreChat) | 自建 ChatGPT 式聊天，支持多家模型与插件 | 46.2k | `MIT` | 2026-10 |
| [Jan](https://github.com/janhq/jan) | 100% 离线的桌面 ChatGPT 替代，数据不出本机 | 45.0k | `自定义` | 2026-10 |
| [Reactive Resume](https://github.com/reactive-resume/reactive-resume) | 隐私优先的简历编辑器，数据存本地 | 44.8k | `MIT` | 2026-10 |
| [ToolJet](https://github.com/ToolJet/ToolJet) | 低代码搭管理后台，能用 AI 生成界面 | 41.1k | `AGPL-3.0` | 2026-10 |
| [Appsmith](https://github.com/appsmithorg/appsmith) | 拖拽搭内部工具与后台，直连数据库和 API | 41.1k | `Apache-2.0` | 2026-10 |
| [Langfuse](https://github.com/langfuse/langfuse) | LLM 应用的可观测与评测，追踪每次调用与成本 | 36.3k | `自定义` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 部署、接入与远程

_先把这一层搭好，后面装什么都轻松。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [RustDesk](https://github.com/rustdesk/rustdesk) | 自建远程桌面，中继与穿透都能自己控，数据不出门 | 127k | `AGPL-3.0` | 2026-10 |
| [Coolify](https://github.com/coollabsio/coolify) | 自建 Vercel/Heroku，Git 推送即部署，带证书与备份 | 63.6k | `Apache-2.0` | 2026-10 |
| [Appwrite](https://github.com/appwrite/appwrite) | 自建后端即服务，账号、数据库、存储、函数都有 | 57.8k | `BSD-3-Clause` | 2026-10 |
| [Headscale](https://github.com/juanfont/headscale) | Tailscale 控制面的自托管实现，组内网不用第三方服务 | 44.9k | `BSD-3-Clause` | 2026-10 |
| [Dokploy](https://github.com/Dokploy/dokploy) | 更轻的 PaaS 面板，Docker 应用与数据库一键起 | 38.0k | `自定义` | 2026-10 |
| [Glance](https://github.com/glanceapp/glance) | 把所有信息源聚成一个自建首页，启动快 | 37.6k | `AGPL-3.0` | 2026-10 |
| [CasaOS](https://github.com/IceWhaleTech/CasaOS) | 把家用小主机变成个人云，应用商店一键装 | 37.4k | `Apache-2.0` | 2026-09 |

<sub>[回到目录](#目录)</sub>

## 为什么值得看

自部署最容易踩的坑是**选了个功能最多但没人维护的项目**。所以这里只保留近一年有提交、许可证明确、有现成 Docker 镜像的项目，并按“先装什么”排序，而不是按功能列表堆砌。

## 收录标准

- 有明确用途，README 能看懂、能跑起来；不收录只发概念或演示视频的项目。
- 许可证明确，仓库未归档；长期不更新的项目会标注并移出主表。
- 同一定位只留一个首选，同类项目放进同一小节横向对比，不做堆砌。
- Stars 只作参考，主要看维护频率、issue 响应和文档质量。
- 每条说明写清“解决什么问题、适合谁”，不搬运项目自述。

## 参与贡献

发现更好的项目、链接失效或说明有误？欢迎开 issue 或直接提交 PR，格式与要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。收录后会在下一次生成时自动带上真实 Stars 与许可证。

## 关于这份清单

- 表里的 Stars、许可证、最近提交都是生成时从 GitHub API 拉取的，不是手写数字，所以不会过期。
- 每次增删项目只改一份精选数据，再跑生成脚本，中英文两个版本与 Stars 同时更新。
- 如果这份清单帮你少翻了十几个仓库，点个 **Star** 是最直接的支持：[⭐ Star awesome-self-hosted](https://github.com/AwesomeRepoHub/awesome-self-hosted/stargazers)

## 许可

内容采用 [MIT](LICENSE) 许可，可自由转载，注明来源即可。项目本身的版权与许可归各作者所有。

---

<sub>本文件由脚本从精选数据与 GitHub API 自动生成，请勿直接编辑；增删条目见 [CONTRIBUTING.md](CONTRIBUTING.md)。</sub>
