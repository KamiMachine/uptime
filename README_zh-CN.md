<div align="right">
  <a title="English" href="README.md"><img src="https://img.shields.io/badge/-English-545759?style=for-the-badge" alt="English"></a>
  <a title="简体中文" href="README_zh-CN.md"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-A31F34?style=for-the-badge" alt="简体中文"></a>
</div>

# KomeStudio 与 KamiMachine — 服务状态页

> **komestudio.com** 与 **kamimachine.com** 的实时运行状态、事故记录与服务健康监控。

[![Uptime](https://img.shields.io/badge/uptime-99.9%25-brightgreen)](https://status.komestudio.com)
[![Status](https://img.shields.io/badge/status-operational-success)](https://status.kamimachine.com)
[![Powered by](https://img.shields.io/badge/powered%20by-UptimeFlare-blue)](https://github.com/lyc8503/UptimeFlare)
[![Deployed on](https://img.shields.io/badge/deployed%20on-Cloudflare%20Workers-orange)](https://workers.cloudflare.com/)

---

## 🌐 状态页入口

| 服务 | 状态页 | 说明 |
|---|---|---|
| **KomeStudio** | [status.komestudio.com](https://status.komestudio.com) | KomeStudio 服务状态监控 |
| **KamiMachine** | [status.kamimachine.com](https://status.kamimachine.com) | KamiMachine 服务状态监控 |

实时查看运行时间、事故报告与计划维护，每分钟自动更新。

---

## ✨ 功能特性

- **实时监控** — 支持 HTTP、HTTPS、TCP、ICMP 检测，每分钟一次
- **全球边缘网络** — 基于 Cloudflare Workers，覆盖全球 300+ 节点
- **事故历史** — 完整记录历史事故与维护窗口
- **即时通知** — 支持 Telegram、Slack、Discord、邮件、Webhook
- **自定义状态徽章** — 可嵌入 README 或网站的 SVG 徽章
- **多语言支持** — 英文、中文等
- **完全无服务器** — 无需管理服务器，零月费

---

## 🔍 关键词

`komestudio 状态` · `komestudio 运行状态` · `komestudio 挂了` · `komestudio 宕机`  
`kamimachine 状态` · `kamimachine 运行状态` · `kamimachine 挂了` · `kamimachine 宕机`  
`komestudio 服务状态` · `kamimachine 事故报告` · `状态页` · `在线监控`

---

## 🛠️ 技术栈

| 层级 | 技术 |
|---|---|
| 前端 | Next.js 14、React、TypeScript、TailwindCSS |
| 后端 | Cloudflare Workers |
| 存储 | Cloudflare KV |
| 监控引擎 | [UptimeFlare](https://github.com/lyc8503/UptimeFlare) |
| CI/CD | GitHub Actions |
| 托管 | Cloudflare Pages + Workers |

---

## 🚀 部署方式

本仓库通过 GitHub Actions 自动部署，每次推送到 `main` 分支即触发。

### 准备工作

- Cloudflare 账号（免费版即可）
- GitHub 账号
- 具有 `Edit Cloudflare Workers` 权限的 Cloudflare API Token

### 部署步骤

1. 在 GitHub 上 **Fork / 使用模板** 创建仓库
2. **添加 Secret**：`CLOUDFLARE_API_TOKEN`
3. **编辑 `uptime.config.ts`** 添加监控项
4. **推送到 `main`** — GitHub Actions 会自动完成部署

详细步骤请参考 [UptimeFlare 官方文档](https://github.com/lyc8503/UptimeFlare)。

---

## 📊 监控服务列表

### KomeStudio (`komestudio.com`)

- 主站 — `https://komestudio.com`
- API 接口 — `https://blog.komestudio.com`
- CDN / 静态资源 — `https://www.komestudio.com`

### KamiMachine (`kamimachine.com`)

- 主站 — `https://kamimachine.com`
- Blog 接口 — `https://blog.kamimachine.com`
- CDN / 静态资源 — `https://www.kamimachine.com`

---

## 🔔 订阅更新

- **RSS 订阅**：`/feed.xml`（如已启用）
- **邮件通知**：通过状态页订阅
- **Telegram**：[@komestudio_status](https://t.me/komestudio_status) *（占位符）*

---

## 📄 开源协议

本项目基于 [UptimeFlare](https://github.com/lyc8503/UptimeFlare) 构建，遵循 MIT 协议。

**KomeStudio** 与 **KamiMachine** 的状态页内容、配置与品牌标识版权归 KomeStudio / KamiMachine 所有。

---

## 🙏 致谢

- 监控引擎：[UptimeFlare](https://github.com/lyc8503/UptimeFlare)

---

<p align="center">
  <strong>KomeStudio</strong> · <a href="https://komestudio.com">komestudio.com</a> &nbsp;|&nbsp;
  <strong>KamiMachine</strong> · <a href="https://kamimachine.com">kamimachine.com</a>
</p>
