# 身份认证 / SSO

替代对象大致对应：**Auth0、Clerk、Firebase Auth、Okta** 等身份与登录。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Auth0、Okta | authentik | [官网](https://goauthentik.io/) · [GitHub](https://github.com/goauthentik/authentik) | 全能自托管 IdP：OIDC/SAML/LDAP/代理登录与可视化 Flow | 学习曲线在 Flow；部分企业能力在 Enterprise | 中等 | 活跃 | 核心 MIT；需 Postgres |
| Auth0、企业 SSO | Keycloak | [官网](https://www.keycloak.org/) · [GitHub](https://github.com/keycloak/keycloak) | 业界常见企业级 IAM，协议与联邦能力强 | 资源占用高；概念多，小团队易过度设计 | 较难 | 活跃 | Apache-2.0；Java，生产建议 Postgres |
| 反向代理 SSO（Homelab） | Authelia | [官网](https://www.authelia.com/) · [GitHub](https://github.com/authelia/authelia) | 挂在 Traefik/Nginx/Caddy 前的轻量登录与 2FA 门禁 | 非完整 CIAM；无 SAML；用户多依赖 LDAP/YAML | 中等 | 活跃 | Apache-2.0；Go 单二进制 |
| Auth0/Clerk 精简版 | Pocket ID | [官网](https://pocket-id.org/) · [GitHub](https://github.com/pocket-id/pocket-id) | 只做 Passkey 的轻量 OIDC 提供方，单容器即可 | 无密码登录；无 SAML；不适合复杂企业联邦 | 简单 | 活跃 | BSD-2-Clause；强制 HTTPS；闲时内存很低 |
| Auth0、B2B SaaS | ZITADEL | [官网](https://zitadel.com/) · [GitHub](https://github.com/zitadel/zitadel) | 云原生身份平台，多组织/B2B 场景友好 | AGPL 与运营模型需评估；比 Pocket ID 重 | 中等 | 活跃 | AGPL-3.0 |
| Clerk、面向应用内嵌 | Logto | [官网](https://logto.io/) · [GitHub](https://github.com/logto-io/logto) | 现代 TypeScript 身份栈，预置登录页与组织/RBAC | 生态与 Keycloak 比仍小；部分能力走 Cloud/商业 | 中等 | 活跃 | MPL-2.0（以仓库为准） |
| 无头身份 API | Ory | [官网](https://www.ory.sh/) · [GitHub](https://github.com/ory) | API 优先的身份组件（Kratos/Hydra 等），可自建登录 UI | 需自行拼装与设计 UX；运维面多 | 较难 | 活跃 | Apache-2.0；适合产品工程团队 |
| 应用内嵌 Auth SDK | SuperTokens | [官网](https://supertokens.com/) · [GitHub](https://github.com/supertokens/supertokens-core) | 把登录嵌进自己前后端的开源方案 | 不是完整企业 IdP；部署与集成模式不同于 Keycloak | 中等 | 活跃 | Apache-2.0 |
