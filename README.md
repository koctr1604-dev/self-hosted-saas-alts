# 本地替代 SaaS 清单

> 开发者都知道「这些东西可以自托管」，但懒得持续收集与对比。本仓库只做脏活：按场景列出靠谱的本地 / 自托管替代，并标明**功能缺口、部署难度、维护状态**。

**最后更新：** 2026-11-05（Asia/Shanghai）

## 这是什么

一份面向开发者的策展列表，不是评测榜，也不是安装教程合集。

- **目标读者**：考虑把部分 SaaS 迁回自己服务器 / 家里实验室的人
- **收录原则**：真实存在、可自托管、有一定社区或明确维护信号；不编造项目
- **诚实原则**：每条都写「相对 SaaS 缺什么」，避免只贴 star 数

许可证：**MIT**（见 [LICENSE](./LICENSE)）。清单中的各开源项目仍遵循其自身许可证。

## 如何使用

1. 打开下方分类，按你想替代的 SaaS 扫表。
2. 先看 **部署难度** 与 **功能缺口**，再点官网 / 仓库。
3. 上线前务必自己核对：许可证（尤其 BUSL / EE / 席位限制）、资源占用、备份与升级路径。
4. 想补充或纠错？见 [CONTRIBUTING.md](./CONTRIBUTING.md)；字段含义见 [data/schema.md](./data/schema.md)。

## 分类索引

| 分类 | 文件 | 大致对照 |
| --- | --- | --- |
| 生产力 / 知识库 | [categories/productivity.md](./categories/productivity.md) | Notion、Confluence、Google Docs |
| 网站 / 产品分析 | [categories/analytics.md](./categories/analytics.md) | Google Analytics、Mixpanel、Plausible |
| 身份认证 / SSO | [categories/auth.md](./categories/auth.md) | Auth0、Clerk、Firebase Auth |
| 监控 / 可观测 / 错误追踪 | [categories/monitoring.md](./categories/monitoring.md) | Datadog、New Relic、Sentry |
| 表单 / 问卷 | [categories/forms-surveys.md](./categories/forms-surveys.md) | Typeform、Google Forms |
| 邮件营销 / 通讯 | [categories/email-marketing.md](./categories/email-marketing.md) | Mailchimp、ConvertKit |
| 网盘 / 文件 / 相册 | [categories/file-storage.md](./categories/file-storage.md) | Dropbox、Google Drive、Google Photos |
| 聊天 / 社区 | [categories/chat-community.md](./categories/chat-community.md) | Slack、Discord |

也可直接看精简目录：[SUMMARY.md](./SUMMARY.md)。

## 字段速览

每个条目包含：

- **SaaS 对照** — 主要替代谁
- **项目名 + 链接** — 官网 / GitHub（或 GitLab）
- **一句话说明**
- **功能缺口** — 相对 SaaS 缺什么、有哪些坑
- **部署难度** — 简单 / 中等 / 较难
- **维护状态** — 活跃 / 一般 / 停更或风险
- **备注** — 许可证、资源、边界情况

完整定义见 [data/schema.md](./data/schema.md)。

## 贡献

欢迎 PR：补条目、更新维护状态、换掉失效链接、纠正许可证描述。请按 [CONTRIBUTING.md](./CONTRIBUTING.md) 填写必填字段，不要提交未核实的项目。

## 免责声明

- 维护状态基于公开信息（文档、发行说明、仓库活跃度等）的快照，**会过时**。
- 「可自托管」≠「生产开箱即用」；邮件投递、合规、高可用需自行评估。
- 本仓库作者与所列项目无隶属关系，也不提供付费咨询保证。

## License

[MIT](./LICENSE) © 2026 koctr
