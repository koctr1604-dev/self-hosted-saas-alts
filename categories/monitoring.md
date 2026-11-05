# 监控 / 可观测 / 错误追踪

替代对象大致对应：**Datadog、New Relic、Sentry**，以及可用性监控。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Datadog、New Relic | SigNoz | [官网](https://signoz.io/) · [GitHub](https://github.com/SigNoz/signoz) | 开源一体化观测：指标 / 日志 / 链路，OTel 原生 | 生态与 Grafana 比更窄；需运维 ClickHouse | 中等 | 活跃 | 核心 MIT；单机 Compose 可试用 |
| Datadog（拼装栈） | Grafana + LGTM | [Grafana](https://grafana.com/oss/) · [Loki](https://grafana.com/oss/loki/) | 业界主流自建观测拼盘：Grafana + Loki/Tempo/Mimir 等 | 组件多、运维成本高；不是「一个安装包替代 Datadog」 | 较难 | 活跃 | 多为 AGPL；灵活但学习曲线陡 |
| Datadog 轻量一体 | OpenObserve | [官网](https://openobserve.ai/) · [GitHub](https://github.com/openobserve/openobserve) | Rust 单二进制向观测平台，对象存储降本 | 成熟度与生态仍追赶；商业功能边界需核对 | 简单 | 活跃 | AGPL-3.0 |
| Sentry | GlitchTip | [官网](https://glitchtip.com/) · [GitLab](https://gitlab.com/glitchtip/glitchtip) | 兼容 Sentry SDK 的轻量错误追踪，还可带简单可用性检查 | 无 Sentry 全套性能剖析 / Session Replay 深度 | 简单 | 活跃 | MIT；代码在 GitLab |
| Sentry（官方自托管） | Sentry Self-Hosted | [文档](https://develop.sentry.dev/self-hosted/) · [GitHub](https://github.com/getsentry/self-hosted) | 功能最全的错误与性能平台自托管发行 | 资源与升级负担大；多数团队最终更倾向 Cloud | 较难 | 活跃 | 自托管许可与功能以官方说明为准 |
| Pingdom、状态页 | Uptime Kuma | [GitHub](https://github.com/louislam/uptime-kuma) | 友好的 HTTP/TCP/DNS 可用性监控与状态页 | 不是 APM/日志平台 | 简单 | 活跃 | MIT；Docker 一键常见 |
| 基础设施实时监控 | Netdata | [官网](https://www.netdata.cloud/) · [GitHub](https://github.com/netdata/netdata) | 节点级实时指标，安装快、图表密 | 长期存档与跨集群关联弱于完整 APM | 简单 | 活跃 | GPL；适合机房/VPS 第一屏 |
| Prometheus 生态 | Prometheus | [官网](https://prometheus.io/) · [GitHub](https://github.com/prometheus/prometheus) | 云原生指标采集与告警的事实标准底座 | 本身不是完整「Datadog UI」；需搭配 Grafana 等 | 中等 | 活跃 | Apache-2.0 |
