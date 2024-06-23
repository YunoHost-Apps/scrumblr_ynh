<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Scrumblr

[![集成程度](https://dash.yunohost.org/integration/scrumblr.svg)](https://dash.yunohost.org/appci/app/scrumblr) ![工作状态](https://ci-apps.yunohost.org/ci/badges/scrumblr.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/scrumblr.maintain.svg)

[![使用 YunoHost 安装 Scrumblr](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=scrumblr)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Scrumblr。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

scrumblr is a web-based simulation of a physical agile kanban board that supports real-time collaboration. it is built using node.js, websockets (using socket.io), CSS3, and jquery. 

**分发版本：** 2021.12.10~ynh1

**演示：** <http://scrumblr.ca/>

## 截图

![Scrumblr 的截图](./doc/screenshots/post-it_demo.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <http://www.scrumblr.ca/>
- 上游应用代码库： <https://framagit.org/colibris/framemo>
- YunoHost 商店： <https://apps.yunohost.org/app/scrumblr>
- 报告 bug： <https://github.com/YunoHost-Apps/scrumblr_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
或
sudo yunohost app upgrade scrumblr -u https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
