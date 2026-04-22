# 🛡️ Awesome IP Purity & Network Privacy

免费 IP 纯净度检测、代理检测、DNS 泄露检测、浏览器指纹检测相关的工具和资源合集。

A curated list of tools and resources for IP purity detection, proxy detection, DNS leak testing, and browser fingerprint analysis.

---

## 🔍 检测工具 / Detection Tools

| 工具 / Tool | 说明 / Description | 链接 / Link |
|---|---|---|
| **IPRisk.top** | 16 源聚合 IP 纯净度评分（0-100）/ 16-source aggregated IP purity score | [iprisk.top](https://iprisk.top) |
| **IPRisk 浏览器环境检测** | WebRTC / DNS / 时区泄露检测 / WebRTC, DNS leak & timezone mismatch scan | [iprisk.top/env](https://iprisk.top/env) |
| **IPRisk 浏览器插件** | Chrome/Edge 实时 IP 漂移监测 / Real-time IP drift alerts | [iprisk.top/extension](https://iprisk.top/extension) |
| ping0.cc | IP 质量风控值检测 / IP quality & risk score check | [ping0.cc](https://ping0.cc) |
| Scamalytics | IP 欺诈评分 / IP fraud score | [scamalytics.com](https://scamalytics.com) |
| BrowserLeaks | 浏览器隐私泄露检测 / Browser privacy leak tests | [browserleaks.com](https://browserleaks.com) |
| whoer.net | IP 匿名度检测 / IP anonymity check | [whoer.net](https://whoer.net) |
| ipleak.net | IP / DNS 泄露检测 / IP & DNS leak test | [ipleak.net](https://ipleak.net) |
| ipcheck.ing | 全能 IP 工具箱（开源）/ All-in-one IP toolbox (open source) | [ipcheck.ing](https://ipcheck.ing) |
| BrowserScan | 浏览器指纹检测 / Browser fingerprint detection | [browserscan.net](https://browserscan.net) |

---

## 🏷️ 常见概念解释 / Key Concepts

| 概念 / Concept | 解释 / Explanation |
|---|---|
| IP 纯净度 / IP Purity | 衡量一个 IP 地址在多个风控数据库中的清洁程度，分数越高越安全 / How clean an IP is across multiple risk databases. Higher = safer. |
| 住宅 IP / Residential IP | 由家庭宽带 ISP 分配的 IP，被平台信任度最高 / Assigned by home ISP, highest trust level on platforms. |
| 机房 IP / Datacenter IP | 由云服务商分配的 IP（AWS、Vultr 等），容易被平台识别并限制 / Assigned by cloud providers, easily flagged by platforms. |
| 代理 / Proxy | 中间转发层，隐藏真实 IP，但会被风控系统检测 / Traffic relay that hides real IP, detectable by fraud systems. |
| DNS 泄露 / DNS Leak | 代理环境下 DNS 请求走了本地 ISP 而非代理通道，暴露真实位置 / DNS queries bypass proxy, revealing real location. |
| WebRTC 泄露 / WebRTC Leak | 浏览器通过 WebRTC 协议泄露真实内网/公网 IP / Browser exposes real IP via WebRTC protocol. |
| 浏览器指纹 / Browser Fingerprint | 通过 Canvas、WebGL、字体等特征组合唯一标识用户设备 / Unique device identification via Canvas, WebGL, fonts, etc. |

---

## 🌐 社区与链接 / Community & Links

- 🌐 [IPRisk.top 官网](https://iprisk.top)
- 🔍 [浏览器环境检测](https://iprisk.top/env)
- 📖 [安全学院 Q&A](https://iprisk.top/academy)
- 📖 [关于 IPRisk.top](https://iprisk.top/about)
- 🤖 [Telegram 机器人 — 发送 IP 即查纯净度](https://t.me/iprisk_top_bot)
- 📢 [Telegram 频道 — 安全上网指南](https://t.me/iprisk_top_channel)

---

*欢迎提交 PR 补充更多工具和资源。/ PRs welcome to add more tools and resources.*
