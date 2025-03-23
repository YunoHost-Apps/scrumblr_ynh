<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Scrumblr для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/scrumblr)](https://ci-apps.yunohost.org/ci/apps/scrumblr/)
![Состояние работы](https://apps.yunohost.org/badge/state/scrumblr)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/scrumblr)

[![Установите Scrumblr с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=scrumblr)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Scrumblr быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

scrumblr is a web-based simulation of a physical agile kanban board that supports real-time collaboration. it is built using node.js, websockets (using socket.io), CSS3, and jquery. 


**Поставляемая версия:** 2021.12.10~ynh2

**Демо-версия:** <http://scrumblr.ca/>

## Снимки экрана

![Снимок экрана Scrumblr](./doc/screenshots/post-it_demo.png)

## :red_circle: Анти-функции

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Документация и ресурсы

- Официальный веб-сайт приложения: <http://www.scrumblr.ca/>
- Репозиторий кода главной ветки приложения: <https://framagit.org/colibris/framemo>
- Магазин YunoHost: <https://apps.yunohost.org/app/scrumblr>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/scrumblr_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
или
sudo yunohost app upgrade scrumblr -u https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
