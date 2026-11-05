# 生产力 / 知识库

替代对象大致对应：**Notion、Confluence、Google Docs** 一类文档与知识库产品。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Notion | AppFlowy | [官网](https://appflowy.com/) · [GitHub](https://github.com/AppFlowy-IO/AppFlowy) | 最接近 Notion 的文档 + 数据库 + 多端客户端组合 | 自托管服务端已商业化，免费档通常仅 1 席；完整团队协作需付费 | 中等 | 活跃 | 客户端偏 AGPL；Cloud 自托管路径与开源边界需先读许可 |
| Notion | AFFiNE | [官网](https://affine.pro/) · [GitHub](https://github.com/toeverything/AFFiNE) | 文档与白板合一，偏可视化笔记与脑暴 | 关系型数据库能力弱于 Notion/AppFlowy；服务端多为 EE 许可 | 简单 | 活跃 | Docker Compose 上手快；自托管免费席位有上限（以官网为准） |
| Notion、Confluence | Outline | [官网](https://www.getoutline.com/) · [GitHub](https://github.com/outline/outline) | 打磨较好的团队 Wiki / 文档库，实时协作体验强 | 无 Notion 式关系数据库；自托管需一定运维经验 | 中等 | 活跃 | BUSL-1.1（非 OSI 开源），到期后转为 Apache-2.0 |
| Notion、Confluence | Docmost | [官网](https://docmost.com/) · [GitHub](https://github.com/docmost/docmost) | 协作 Wiki，带轻量表格/看板，可从 Confluence/Notion 迁移 | 数据库深度不如 Notion；部分企业能力在付费版 | 简单 | 活跃 | AGPL-3.0；Compose 依赖 Postgres + Redis |
| 个人知识库（Notion/Obsidian 向） | SiYuan | [官网](https://b3log.org/siyuan/) · [GitHub](https://github.com/siyuan-note/siyuan) | 隐私优先的块级个人知识库，本地/自建同步 | 非实时多人协作产品；部分高级能力收费 | 简单 | 活跃 | AGPL-3.0；更适合个人而非团队 Wiki |
| Confluence、文档站 | BookStack | [官网](https://www.bookstackapp.com/) · [代码托管](https://codeberg.org/bookstack/BookStack) | 书—章—页结构清晰的文档系统，导航友好 | 无白板/数据库；协作形态偏传统文档 | 简单 | 活跃 | MIT；PHP + MySQL/MariaDB/Postgres |
| 文档 Wiki | Wiki.js | [官网](https://js.wiki/) · [GitHub](https://github.com/requarks/wiki) | 现代 Wiki，可与 Git 存储联动 | 不是 Notion 工作区；实时多人编辑体验因版本而异 | 中等 | 活跃 | AGPL-3.0 |
| Evernote、个人笔记 | Joplin | [官网](https://joplinapp.org/) · [GitHub](https://github.com/laurent22/joplin) | Markdown 笔记，支持端到端加密与多端同步 | 非团队实时协作；需自备同步目标（如 Nextcloud/WebDAV） | 简单 | 活跃 | MIT；「自托管」重点在同步后端而非完整 SaaS 工作区 |
