<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Adminer

[![集成程度](https://dash.yunohost.org/integration/adminer.svg)](https://ci-apps.yunohost.org/ci/apps/adminer/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)

[![使用 YunoHost 安装 Adminer](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Adminer。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

AdminerEvo is a web-based database management interface, with a focus on security, user experience, performance, functionality and size. It is available for download as a single self-contained PHP file, making it easy to deploy anywhere. AdminerEvo works out of the box with MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch and MongoDB. In addition, there are plugins for SimpleDB, Firebird and ClickHouse. AdminerEvo is developed by the AdminerEvo community and is a continuation of the Adminer project by Jakub Vrána.

**分发版本：** 4.8.4~ynh1

**演示：** <https://demo.adminer.org/adminer.php?username=>

## 截图

![Adminer 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <https://docs.adminerevo.org/>
- 上游应用代码库： <https://github.com/adminerevo/adminerevo>
- YunoHost 商店： <https://apps.yunohost.org/app/adminer>
- 报告 bug： <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
或
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
