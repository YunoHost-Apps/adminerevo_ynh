<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# AdminerEvo untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/adminerevo.svg)](https://ci-apps.yunohost.org/ci/apps/adminerevo/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/adminerevo.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/adminerevo.maintain.svg)

[![Pasang AdminerEvo dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminerevo)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang AdminerEvo secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

AdminerEvo is a web-based database management interface, with a focus on security, user experience, performance, functionality and size. It is available for download as a single self-contained PHP file, making it easy to deploy anywhere. AdminerEvo works out of the box with MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch and MongoDB. In addition, there are plugins for SimpleDB, Firebird and ClickHouse. AdminerEvo is developed by the AdminerEvo community and is a continuation of the Adminer project by Jakub Vrána.

**Versi terkirim:** 4.8.4~ynh1

## Tangkapan Layar

![Tangkapan Layar pada AdminerEvo](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://docs.adminerevo.org>
- Depot kode aplikasi hulu: <https://github.com/adminerevo/adminerevo>
- Gudang YunoHost: <https://apps.yunohost.org/app/adminerevo>
- Laporkan bug: <https://github.com/YunoHost-Apps/adminerevo_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/adminerevo_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminerevo_ynh/tree/testing --debug
atau
sudo yunohost app upgrade adminerevo -u https://github.com/YunoHost-Apps/adminerevo_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
