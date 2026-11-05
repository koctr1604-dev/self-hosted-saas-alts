# 网站 / 产品分析

替代对象大致对应：**Google Analytics、Mixpanel、Plausible** 等流量与产品分析。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Google Analytics、Plausible | Umami | [官网](https://umami.is/) · [GitHub](https://github.com/umami-software/umami) | 轻量无 Cookie 网站分析，Docker + Postgres 即可 | 深度产品分析（会话画像、实验）弱于 Mixpanel/PostHog | 简单 | 活跃 | MIT；资源占用低，适合先上线 |
| Google Analytics、Plausible | Plausible CE | [官网](https://plausible.io/) · [GitHub](https://github.com/plausible/analytics) | 隐私优先的流量看板，脚本极小 | 需跑 ClickHouse；功能相对「专注」而非全家桶 | 中等 | 活跃 | AGPL；Cloud 与 Community Edition 分开 |
| Google Analytics | Matomo | [官网](https://matomo.org/) · [GitHub](https://github.com/matomo-org/matomo) | 功能最接近传统 GA 的开源分析套件 | 运维与插件生态更重；部分能力（热图等）为付费插件 | 中等 | 活跃 | GPL；PHP + MySQL/MariaDB |
| Mixpanel、Amplitude、产品分析 | PostHog | [官网](https://posthog.com/) · [GitHub](https://github.com/PostHog/posthog) | 事件分析 + 录像 + Feature Flag + 实验等一体化 | 自托管官方定位偏 hobby，生产更推 Cloud；机器规格要求高 | 较难 | 活跃 | 核心 MIT，`ee/` 另有许可；建议 ≥16GB RAM |
| Plausible 类轻量统计 | GoatCounter | [官网](https://www.goatcounter.com/) · [GitHub](https://github.com/arp242/goatcounter) | 极简站点统计，Go 单二进制 + SQLite/Postgres | 报表维度少；不是产品分析平台 | 简单 | 活跃 | EUPL 变体；适合静态站/博客 |
| 网站 + 产品分析 | OpenPanel | [官网](https://openpanel.dev/) · [GitHub](https://github.com/Openpanel-dev/openpanel) | 试图同时覆盖 Web 与产品分析的自托管方案 | 相对 PostHog 生态更小；栈含 ClickHouse 等 | 中等 | 活跃 | AGPL；以官网部署文档为准 |
| GA 轻量替代 | Ackee | [官网](https://ackee.electerious.com/) · [GitHub](https://github.com/electerious/Ackee) | Node 写的隐私友好分析，界面简洁 | 功能集更窄；社区体量小于 Umami/Plausible | 简单 | 一般 | MIT；适合个人站点 |
