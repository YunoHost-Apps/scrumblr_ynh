<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Scrumblr YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/scrumblr)](https://ci-apps.yunohost.org/ci/apps/scrumblr/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/scrumblr)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/scrumblr)

[![Instalatu Scrumblr YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=scrumblr)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Scrumblr YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

scrumblr is a web-based simulation of a physical agile kanban board that supports real-time collaboration. it is built using node.js, websockets (using socket.io), CSS3, and jquery. 


**Paketatutako bertsioa:** 2021.12.10~ynh2

**Demoa:** <http://scrumblr.ca/>

## Pantaila-argazkiak

![Scrumblr(r)en pantaila-argazkia](./doc/screenshots/post-it_demo.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://www.scrumblr.ca/>
- Jatorrizko aplikazioaren kode-gordailua: <https://framagit.org/colibris/framemo>
- YunoHost Denda: <https://apps.yunohost.org/app/scrumblr>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/scrumblr_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
edo
sudo yunohost app upgrade scrumblr -u https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
