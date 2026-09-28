# 🔍 Awesome IP Purity & Network Privacy

[![IPRisk.top](https://img.shields.io/badge/Powered_by-IPRisk.top-blue?style=flat-square)](https://iprisk.top)

**IP 纯净度检测 / 代理检测 / DNS 泄露 / 浏览器指纹 相关工具与资源合集**

Curated list of IP reputation, proxy detection, DNS leak, and browser fingerprint tools & resources.

> IP 信誉、出口地区、DNS、WebRTC、时区和浏览器环境，都会影响你排查 ChatGPT / Claude / TikTok / Amazon 等平台问题时的判断。
>
> IP reputation, exit region, DNS, WebRTC, timezone, and browser environment all matter when troubleshooting platforms such as ChatGPT / Claude / TikTok / Amazon.

---

## 📋 目录 / Table of Contents

- [🔍 Awesome IP Purity \& Network Privacy](#-awesome-ip-purity--network-privacy)
  - [📋 目录 / Table of Contents](#-目录--table-of-contents)
  - [🔍 检测工具 / Detection Tools](#-检测工具--detection-tools)
  - [📊 使用方式 / Ways to Use](#-使用方式--ways-to-use)
  - [🛡️ 代理方案参考 / Proxy Provider Guide](#️-代理方案参考--proxy-provider-guide)
  - [🏷️ 常见概念解释 / Key Concepts](#️-常见概念解释--key-concepts)
  - [🏷️ 嵌入徽章 / Embed Badge](#️-嵌入徽章--embed-badge)
  - [🌐 社区与链接 / Community \& Links](#-社区与链接--community--links)

---

## 🔍 检测工具 / Detection Tools

| 工具 / Tool | 说明 / Description | 链接 / Link |
|---|---|---|
| **IPRisk.top** | 16 个独立来源交叉检测 IP 纯净度评分（0-100），保留评分明细和来源标签 / Cross-checks 16 independent sources for a 0-100 IP reputation score with source-level details | [iprisk.top](https://iprisk.top) |
| **IPRisk 浏览器环境检测** | 出口 IP、WebRTC、DNS、时区、语言和浏览器环境一致性检测 / Exit IP, WebRTC, DNS, timezone, language, and browser-environment consistency checks | [iprisk.top/env](https://iprisk.top/env) |
| **IPRisk Sentinel 浏览器插件** | Chrome/Edge 插件，持续比对出口 IP、DNS 与 WebRTC 基准 / Chrome/Edge extension for exit IP, DNS, and WebRTC baseline monitoring | [iprisk.top/extension](https://iprisk.top/extension) |
| **IPRisk 批量查询** | 支持批量提交 IP、查看任务进度和导出检测结果 / Submit IPs in batches, track job progress, and export results | [iprisk.top/batch](https://iprisk.top/batch) |
| **IPRisk API** | 面向系统集成和自动化检测的 REST API，返回统一的结构化结果 / REST API for system integration and automated checks with consistent structured results | [iprisk.top/api](https://iprisk.top/api) |
| **IPRisk 控制台** | 管理 API Key、套餐额度、批量任务、调用和账单 / Manage API keys, plan credits, batch jobs, usage, and billing | [iprisk.top/console](https://iprisk.top/console) |
| ping0.cc | IP 质量风控值检测 / IP quality & risk score check | [ping0.cc](https://ping0.cc) |
| Scamalytics | IP 欺诈评分 / IP fraud score | [scamalytics.com](https://scamalytics.com) |
| BrowserLeaks | 浏览器隐私泄露检测 / Browser privacy leak tests | [browserleaks.com](https://browserleaks.com) |
| whoer.net | IP 匿名度检测 / IP anonymity check | [whoer.net](https://whoer.net) |
| ipleak.net | IP / DNS 泄露检测 / IP & DNS leak test | [ipleak.net](https://ipleak.net) |
| ipcheck.ing | 全能 IP 工具箱（开源）/ All-in-one IP toolbox (open source) | [ipcheck.ing](https://ipcheck.ing) |
| BrowserScan | 浏览器指纹检测 / Browser fingerprint detection | [browserscan.net](https://browserscan.net) |

---

## 📊 使用方式 / Ways to Use

| 使用方式 / Access | 说明 / Description |
|---|---|
| 网页检测 / Web check | 未登录用户每小时可免费检测 10 次，登录后每小时可免费检测 30 次 / Visitors receive 10 free checks per hour; signed-in users receive 30 |
| 专业功能 / Professional features | 订阅用户可使用批量查询、API 和更高用量 / Subscribers can use batch queries, API access, and higher usage allowances |

免费与订阅用户使用相同的数据来源和评分标准。

Free and subscribed users receive the same data sources and scoring standards.

---

## 🛡️ 代理方案参考 / Proxy Provider Guide

IP 不够稳定或风险信号较多时，可以按 AI 服务、跨境电商、TikTok / 社媒运营、自建节点等场景比较住宅代理、住宅 IP VPS、固定 IP 和浏览器环境工具。采购后建议把交付 IP 放到 IPRisk 重新检测，核对网络类型、代理信号、黑名单和来源明细。

When an IP is unstable or returns multiple risk signals, compare residential proxies, residential IP VPS, fixed IPs, and browser-environment tools by use case: AI services, cross-border e-commerce, TikTok/social media, or self-hosted routes. After purchase, test delivered IPs with IPRisk to review network type, proxy signals, blacklists, and source details.

👉 [代理方案参考 / Proxy Provider Guide](https://iprisk.top/proxy)

---

## 🏷️ 常见概念解释 / Key Concepts

| 概念 / Concept | 解释 / Explanation |
|---|---|
| IP 纯净度 / IP Reputation | 一个 IP 在多类网络属性、代理、黑名单、滥用和威胁情报来源中的综合信号；分数越高代表当前观察到的负面信号越少 / Combined signals across network classification, proxy, blacklist, abuse, and threat-intelligence sources. Higher means fewer currently observed negative signals. |
| 住宅 IP / Residential IP | 通常由接入运营商分配给家庭或终端宽带用户；仍需要核对历史记录和共享情况 / Usually assigned by access ISPs to home or broadband users; history and sharing still need review. |
| 多源 ISP / Dual ISP | 多个来源同时确认 ISP/住宅或运营商属性，且无明显污染时通常属于高纯净区间 / Multiple sources confirm ISP/residential or carrier attributes; usually high reputation when no contamination is observed. |
| 移动网络 / Mobile IP | 蜂窝或移动运营商出口，干净时通常信誉较高，但地区、共享和 NAT 情况仍需结合来源判断 / Cellular carrier exits can score highly when clean, but region, sharing, and NAT should still be reviewed. |
| 静态住宅 / Static Residential | 具有固定出口特征的 ISP/住宅类地址，通常介于住宅宽带和企业/托管网络之间 / ISP/residential-style address with a stable exit; often between home broadband and business/hosting networks. |
| 企业 IP / Business IP | 企业或商业网络地址；干净时可用性较好，但暴露端口、共享服务和历史记录会影响评分 / Business or corporate network address; can be usable when clean, but exposed ports, shared services, and history affect the score. |
| 机房 IP / Datacenter IP | 云服务或托管网络地址；不等于一定有问题，但很多对网络信誉敏感的场景会更谨慎对待 / Cloud or hosting-network address; not automatically bad, but often treated more carefully in reputation-sensitive workflows. |
| 代理 / Proxy | 中间转发层，可能是住宅、企业、机房或公开代理；需要看供应商、共享程度和历史信号 / Traffic relay that may be residential, business, datacenter, or public proxy; provider, sharing, and history matter. |
| DNS 泄露 / DNS Leak | 网页流量和 DNS 解析走了不同线路，可能导致解析器地区与出口 IP 不一致 / Web traffic and DNS resolution follow different routes, causing resolver region and exit IP mismatch. |
| WebRTC 泄露 / WebRTC Leak | 浏览器 WebRTC 可能暴露与当前出口不同的公网地址或本地网络线索 / WebRTC may expose a public address or local-network clue different from the current exit. |
| 浏览器指纹 / Browser Fingerprint | 通过 Canvas、WebGL、字体、语言、时区等特征组合识别浏览器环境 / Browser-environment identification using Canvas, WebGL, fonts, language, timezone, and related signals. |

---

## 🏷️ 嵌入徽章 / Embed Badge

在你的网站展示 IP 纯净度评分 / Show IP reputation scores on your website:

[![IPRisk](https://iprisk.top/badge/1.1.1.1)](https://iprisk.top/ip/1.1.1.1) [![IP Verified](https://iprisk.top/badge/trust-seal.svg)](https://iprisk.top)

```html
<a href="https://iprisk.top/ip/YOUR_IP" target="_blank">
  <img src="https://iprisk.top/badge/YOUR_IP" alt="IPRisk Score" />
</a>

<a href="https://iprisk.top" target="_blank">
  <img src="https://iprisk.top/badge/trust-seal.svg" width="160" />
</a>
```

## 🌐 社区与链接 / Community & Links

- 🌐 [IPRisk.top 官网](https://iprisk.top)
- 🔍 [浏览器环境检测](https://iprisk.top/env)
- 🧩 [IPRisk Sentinel 浏览器插件](https://iprisk.top/extension)
- 🛡️ [代理方案参考 / Proxy Guide](https://iprisk.top/proxy)
- 📊 [批量查询](https://iprisk.top/batch)
- 🔌 [API 文档](https://iprisk.top/api)
- 🖥️ [控制台](https://iprisk.top/console)
- 📖 [安全学院 Q&A](https://iprisk.top/academy)
- 📖 [关于 IPRisk.top](https://iprisk.top/about)
- 🤖 [Telegram 机器人 — 发送 IP 即查纯净度](https://t.me/iprisk_top_bot)
- 📢 [Telegram 频道 — IP 情报与网络排查](https://t.me/iprisk_top_channel)
