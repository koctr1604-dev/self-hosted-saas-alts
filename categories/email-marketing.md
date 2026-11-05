# 邮件营销 / 通讯

替代对象大致对应：**Mailchimp、ConvertKit**；另附「投递基建」类工具以免混淆。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Mailchimp、ConvertKit（通讯） | listmonk | [官网](https://listmonk.app/) · [GitHub](https://github.com/knadh/listmonk) | 高性能自托管通讯与列表管理，单二进制 + Postgres | 无完整营销自动化旅程；需自备 SMTP/ESP | 简单 | 活跃 | AGPL；内存占用极低，适合大列表 |
| Mailchimp（视觉编辑通讯） | Keila | [官网](https://keila.io/) · [GitHub](https://github.com/pentacent/keila) | 德系开源通讯工具，块编辑器与表单/分段齐全 | 自动化旅程仍在路线图；生态小于 Mailchimp | 简单 | 活跃 | AGPL；Docker 官方镜像 |
| Mailchimp 营销自动化 | Mautic | [官网](https://www.mautic.org/) · [GitHub](https://github.com/mautic/mautic) | 开源营销自动化：线索评分、落地页、 drip 等 | PHP 栈重；升级与插件维护成本高 | 较难 | 活跃 | GPL；最接近「全功能 Mailchimp」 |
| 通讯（CMS 一体） | Ghost | [官网](https://ghost.org/) · [GitHub](https://github.com/TryGhost/Ghost) | 发布平台自带会员与 Newsletter 能力 | 不是通用 ESP；复杂分段/自动化有限 | 中等 | 活跃 | MIT；偏内容站 + 订阅 |
| 老牌列表管理 | phpList | [官网](https://www.phplist.org/) · [GitHub](https://github.com/phpList/phplist3) | 经典开源邮件列表管理器 | UI 与现代体验差距大 | 中等 | 一般 | AGPL；适合遗留迁移 |
| SendGrid/Mailgun（投递） | Postal | [官网](https://docs.postalserver.io/) · [GitHub](https://github.com/postalserver/postal) | 自托管邮件投递平台，不是通讯编辑器 | **不能**单独替代 Mailchimp 的活动编辑与列表运营 | 较难 | 活跃 | 常与 listmonk/Mautic 搭配；运维要求高 |
