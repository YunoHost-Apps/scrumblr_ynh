<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Scrumblr untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/scrumblr)](https://ci-apps.yunohost.org/ci/apps/scrumblr/)
![Status kerja](https://apps.yunohost.org/badge/state/scrumblr)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/scrumblr)

[![Pasang Scrumblr dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=scrumblr)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Scrumblr secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

scrumblr is a web-based simulation of a physical agile kanban board that supports real-time collaboration. it is built using node.js, websockets (using socket.io), CSS3, and jquery. 


**Versi terkirim:** 2021.12.10~ynh2

**Demo:** <http://scrumblr.ca/>

## Tangkapan Layar

![Tangkapan Layar pada Scrumblr](./doc/screenshots/post-it_demo.png)

## :red_circle: Antifitur

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <http://www.scrumblr.ca/>
- Depot kode aplikasi hulu: <https://framagit.org/colibris/framemo>
- Gudang YunoHost: <https://apps.yunohost.org/app/scrumblr>
- Laporkan bug: <https://github.com/YunoHost-Apps/scrumblr_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
atau
sudo yunohost app upgrade scrumblr -u https://github.com/YunoHost-Apps/scrumblr_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
