<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Scrumblr pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/scrumblr.svg)](https://dash.yunohost.org/appci/app/scrumblr) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/scrumblr.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/scrumblr.maintain.svg)

[![Installer Scrumblr avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=scrumblr)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Scrumblr rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

scrumblr is a web-based simulation of a physical agile kanban board that supports real-time collaboration. it is built using node.js, websockets (using socket.io), CSS3, and jquery. 

**Version incluse :** 2021.12.10~ynh1

**Démo :** <http://scrumblr.ca/>

## Captures d’écran

![Capture d’écran de Scrumblr](./doc/screenshots/post-it_demo.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <http://www.scrumblr.ca/>
- Dépôt de code officiel de l’app : <https://framagit.org/colibris/framemo>
- YunoHost Store : <https://apps.yunohost.org/app/scrumblr>
- Signaler un bug : <https://github.com/YunoHost-Apps/scrumblr_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
ou
sudo yunohost app upgrade scrumblr -u https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
