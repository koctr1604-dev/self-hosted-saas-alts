# 表单 / 问卷

替代对象大致对应：**Typeform、Google Forms**。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Typeform、产品内调研 | Formbricks | [官网](https://formbricks.com/) · [GitHub](https://github.com/formbricks/formbricks) | 现代表单 + 站内/链接触发调研，体验管理向开源方案 | SSO/审计等常在 Enterprise；默认遥测需自行关闭 | 简单 | 活跃 | AGPL 核心；Docker 友好 |
| Typeform（对话式） | HeyForm | [官网](https://heyform.net/) · [GitHub](https://github.com/heyform/heyform) | 偏一问一答的对话式表单构建器 | 产品内调研能力弱于 Formbricks；社区更小 | 简单 | 活跃 | AGPL-3.0；Community Edition 镜像 |
| Google Forms、站点表单 | OpnForm | [官网](https://opnform.com/) · [GitHub](https://github.com/JhumanJ/OpnForm) | 日常网站用拖拽表单，逻辑与设计较灵活 | 企业级调研方法论弱于 LimeSurvey | 中等 | 活跃 | AGPL；Laravel + Nuxt |
| 复杂调研 / 学术问卷 | LimeSurvey | [官网](https://www.limesurvey.org/) · [GitHub](https://github.com/LimeSurvey/LimeSurvey) | 题型与配额/随机/多语言极强的老牌问卷系统 | UI 偏传统；安装与配置学习成本高 | 中等 | 活跃 | GPL-2.0；PHP 栈 |
| 可嵌入表单平台 | Form.io | [官网](https://www.form.io/) · [GitHub](https://github.com/formio/formio) | 开发者向表单与数据 API 平台 | 完整商业能力与开源边界需仔细区分 | 中等 | 活跃 | 开源核心 MIT；企业版另计 |
| Nextcloud 生态表单 | Nextcloud Forms | [应用页](https://apps.nextcloud.com/apps/forms) · [GitHub](https://github.com/nextcloud/forms) | 挂在 Nextcloud 上的简单表单，适合已有 NC 的团队 | 不是独立 Typeform；题型与主题有限 | 简单 | 活跃 | AGPL；前提是已部署 Nextcloud |
