<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# AdminerEvo YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/adminerevo.svg)](https://ci-apps.yunohost.org/ci/apps/adminerevo/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/adminerevo.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/adminerevo.maintain.svg)

[![Instalatu AdminerEvo YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminerevo)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek AdminerEvo YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

AdminerEvo is a web-based database management interface, with a focus on security, user experience, performance, functionality and size. It is available for download as a single self-contained PHP file, making it easy to deploy anywhere. AdminerEvo works out of the box with MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch and MongoDB. In addition, there are plugins for SimpleDB, Firebird and ClickHouse. AdminerEvo is developed by the AdminerEvo community and is a continuation of the Adminer project by Jakub Vrána.

**Paketatutako bertsioa:** 4.8.4~ynh1

## Pantaila-argazkiak

![AdminerEvo(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://docs.adminerevo.org>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/adminerevo/adminerevo>
- YunoHost Denda: <https://apps.yunohost.org/app/adminerevo>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/adminerevo_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/adminerevo_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminerevo_ynh/tree/testing --debug
edo
sudo yunohost app upgrade adminerevo -u https://github.com/YunoHost-Apps/adminerevo_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
