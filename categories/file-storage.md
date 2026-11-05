# 网盘 / 文件同步 / 相册

替代对象大致对应：**Dropbox、Google Drive**；相册类对照 **Google Photos**。

| SaaS 对照 | 项目名 | 链接 | 一句话说明 | 功能缺口 | 部署难度 | 维护状态 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Google Drive、Dropbox | Nextcloud | [官网](https://nextcloud.com/) · [GitHub](https://github.com/nextcloud/server) | 最接近「全家桶网盘」：同步、分享、办公套件与应用生态 | 全家桶开启后资源与维护变重；体验因插件而异 | 中等 | 活跃 | AGPL；社区版即可自托管 |
| Dropbox（高效同步） | Seafile | [官网](https://www.seafile.com/) · [GitHub](https://github.com/haiwen/seafile) | 块级同步，大文件/多文件场景性能出色 | 应用生态小于 Nextcloud；社区版与专业版功能差 | 中等 | 活跃 | 开源组件 + 商业版并存 |
| Google Photos | Immich | [官网](https://immich.app/) · [GitHub](https://github.com/immich-app/immich) | 自托管相册：备份、机器学习搜图、多端 App | **不是**通用网盘；仍处快速迭代，升级需跟公告 | 中等 | 活跃 | AGPL；多容器 Compose |
| 轻量 Web 文件管理 | FileBrowser | [官网](https://filebrowser.org/) · [GitHub](https://github.com/filebrowser/filebrowser) | 给已有目录加一个干净的 Web 管理界面 | 无桌面同步客户端；不适合当完整 Drive 替代 | 简单 | 活跃 | Apache-2.0 |
| 多端 P2P 同步 | Syncthing | [官网](https://syncthing.net/) · [GitHub](https://github.com/syncthing/syncthing) | 无中心服务器的连续文件同步 | 无「网盘网页分享」产品形态；需理解设备拓扑 | 简单 | 活跃 | MPL-2.0 |
| Google Drive 类（另一流派） | ownCloud | [官网](https://owncloud.com/) · [GitHub](https://github.com/owncloud/core) | Nextcloud 同源脉络的企业文件协作平台 | 社区版能力与商业版边界需核对 | 中等 | 活跃 | 开源核心 + 企业发行 |
| S3 对象存储 | MinIO | [官网](https://min.io/) · [GitHub](https://github.com/minio/minio) | 兼容 S3 API 的高性能对象存储 | 不是面向终端用户的网盘 UI | 中等 | 活跃 | AGPL；常作为其它自托管应用的后端 |
