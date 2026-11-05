# 聊天 / 社区

替代对象大致对应：**Slack、Discord**；论坛类可对照 Discourse 生态。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Slack | Mattermost | [官网](https://mattermost.com/) · [GitHub](https://github.com/mattermost/mattermost) | 最接近 Slack 体验的团队聊天，DevOps 集成多 | 部分企业功能在付费版；语音/社区娱乐向弱于 Discord | 中等 | 活跃 | 开源版 + 商业版 |
| Slack、客服聚合 | Rocket.Chat | [官网](https://www.rocket.chat/) · [GitHub](https://github.com/RocketChat/Rocket.Chat) | 功能面宽的团队聊天，含 Omnichannel 客服向能力 | 部署与版本升级相对重 | 中等 | 活跃 | MIT（核心以仓库为准） |
| Slack（异步主题流） | Zulip | [官网](https://zulip.com/) · [GitHub](https://github.com/zulip/zulip) | 以 Topic 线程组织讨论，适合深度异步协作 | 学习曲线；「频道时间线」习惯需调整 | 中等 | 活跃 | Apache-2.0 |
| Discord（社区） | Stoat（原 Revolt） | [官网](https://stoat.chat/) · [GitHub](https://github.com/stoatchat) | Discord 风格社区：服务器、角色、语音等 | 相对年轻；自托管语音/完整度仍在演进 | 中等 | 活跃 | 原名 Revolt；以 stoat.chat 为准 |
| Slack/Discord（联邦） | Element + Matrix | [Element](https://element.io/) · [Matrix](https://matrix.org/) · [Synapse](https://github.com/element-hq/synapse) | 联邦加密即时通讯，可桥接其它网络 | Homeserver 运维不简单；桥接质量参差 | 较难 | 活跃 | 适合要联邦/E2EE 的团队 |
| 论坛社区 | Discourse | [官网](https://www.discourse.org/) · [GitHub](https://github.com/discourse/discourse) | 现代论坛标准答案，插件与信任体系成熟 | 不是实时 IM；邮件/Sidekiq 等依赖要配好 | 中等 | 活跃 | GPL；Docker 官方安装常见 |
| 轻量团队聊天 | Twake | [官网](https://twake.app/) · [GitHub](https://github.com/linagora/Twake) | 开源协作套件中的聊天与工作区组件 | 生态与 Mattermost 比更小 | 中等 | 一般 | 适合已看 Linagora 栈的团队 |
