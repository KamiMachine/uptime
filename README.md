<div align="right">
  <a title="English" href="README.md"><img src="https://img.shields.io/badge/-English-A31F34?style=for-the-badge" alt="English" /></a>
  <a title="简体中文" href="README_zh-CN.md"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-545759?style=for-the-badge" alt="简体中文"></a>
</div>

# KomeStudio & KamiMachine — Status Page

> Live uptime monitoring, incident history, and service health for **komestudio.com** and **kamimachine.com**.

[![Uptime](https://img.shields.io/badge/uptime-99.9%25-brightgreen)](https://status.komestudio.com)
[![Status](https://img.shields.io/badge/status-operational-success)](https://status.kamimachine.com)
[![Powered by](https://img.shields.io/badge/powered%20by-UptimeFlare-blue)](https://github.com/lyc8503/UptimeFlare)
[![Deployed on](https://img.shields.io/badge/deployed%20on-Cloudflare%20Workers-orange)](https://workers.cloudflare.com/)

---

## 🌐 Live Status Pages

| Service | Status Page | Description |
|---|---|---|
| **KomeStudio** | [status.komestudio.com](https://status.komestudio.com) | Status page for KomeStudio services |
| **KamiMachine** | [status.kamimachine.com](https://status.kamimachine.com) | Status page for KamiMachine services |

Check real-time uptime, incident reports, and scheduled maintenance for all our services — updated every minute.

---

## ✨ Features

- **Real-time monitoring** — HTTP, HTTPS, TCP, ICMP checks every minute
- **Global edge network** — Powered by Cloudflare Workers, deployed to 300+ locations worldwide
- **Incident history** — Full timeline of past incidents and maintenance windows
- **Instant notifications** — Telegram, Slack, Discord, Email, and Webhook alerts
- **Custom status badges** — Embeddable SVG badges for your README or website
- **Multi-language support** — English, Chinese, and more
- **100% serverless** — No servers to manage, no monthly hosting costs

---

## 🔍 Keywords

`komestudio status` · `komestudio uptime` · `komestudio down` · `is komestudio down`  
`kamimachine status` · `kamimachine uptime` · `kamimachine down` · `is kamimachine down`  
`komestudio service status` · `kamimachine incident report` · `status page` · `uptime monitor`

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 14, React, TypeScript, TailwindCSS |
| Backend | Cloudflare Workers |
| Storage | Cloudflare KV |
| Monitoring Engine | [UptimeFlare](https://github.com/lyc8503/UptimeFlare) |
| CI/CD | GitHub Actions |
| Hosting | Cloudflare Pages + Workers |

---

## 🚀 Deployment

This repo is auto-deployed via GitHub Actions on every push to `main`.

### Prerequisites

- Cloudflare account (free tier is enough)
- GitHub account
- Cloudflare API Token with `Edit Cloudflare Workers` permission

### Setup

1. **Fork / Use this template** on GitHub
2. **Add repository secret**: `CLOUDFLARE_API_TOKEN`
3. **Edit `uptime.config.ts`** to add your monitors
4. **Push to `main`** — GitHub Actions handles the rest

For detailed setup instructions, see the [UptimeFlare documentation](https://github.com/lyc8503/UptimeFlare).

---

## 📊 Monitored Services

### KomeStudio (`komestudio.com`)

- Main website — `https://komestudio.com`
- Blog endpoint — `https://blog.komestudio.com`
- CDN / assets — `https://www.komestudio.com`

### KamiMachine (`kamimachine.com`)

- Main website — `https://kamimachine.com`
- Blog endpoint — `https://blog.kamimachine.com`
- CDN / assets — `https://www.kamimachine.com`

---

## 🔔 Subscribe to Updates

- **RSS feed**: `/feed.xml`
- **Email alerts**: Đăng ký qua trang status
- **Telegram**: [@komestudio](https://t.me/komestudio) *(placeholder)*

---

## 📄 License

This project is built on top of [UptimeFlare](https://github.com/lyc8503/UptimeFlare), which is licensed under the MIT License.

Status page content, configuration, and branding for **KomeStudio** and **KamiMachine** are © KomeStudio / KamiMachine. All rights reserved.

---

## 🙏 Credits

- Monitoring engine: [UptimeFlare](https://github.com/lyc8503/UptimeFlare)

---

<p align="center">
  <strong>KomeStudio</strong> · <a href="https://komestudio.com">komestudio.com</a> &nbsp;|&nbsp;
  <strong>KamiMachine</strong> · <a href="https://kamimachine.com">kamimachine.com</a>
</p>
