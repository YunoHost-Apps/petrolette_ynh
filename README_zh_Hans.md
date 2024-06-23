<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Petrolette

[![集成程度](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![工作状态](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)

[![使用 YunoHost 安装 Petrolette](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=petrolette)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Petrolette。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Pétrolette is a news reader that doesn't know you

Pétrolette is fully self-contained, makes no external call whatsoever, and embarks a total of zero tracker or "analysis" tool. Needless to say she is also completely ad-free.

The application has 2 modes 
- multi user : each user store is own config itself.
- mono user : configuration is store locally in the server. Each visitor see the same page. 

For now, there is no any mechanism included for feed protection. Any visitor can modify the feed list.


**分发版本：** 1.7.0~ynh1

**演示：** <https://petrolette.space>

## 截图

![Petrolette 的截图](./doc/screenshots/petrolette.webp)

## 文档与资源

- 官方应用网站： <https://framagit.org/yphil/petrolette>
- 上游应用代码库： <https://framagit.org/yphil/petrolette>
- YunoHost 商店： <https://apps.yunohost.org/app/petrolette>
- 报告 bug： <https://github.com/YunoHost-Apps/petrolette_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
或
sudo yunohost app upgrade petrolette -u https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
