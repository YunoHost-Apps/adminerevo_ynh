<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Adminer pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/adminer.svg)](https://ci-apps.yunohost.org/ci/apps/adminer/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)

[![Installer Adminer avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Adminer rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

AdminerEvo est une interface de gestion de la base de données basée sur le Web, en mettant l'accent sur la sécurité, l'expérience utilisateur, les performances, les fonctionnalités et la taille. Il est disponible en téléchargement comme un seul fichier PHP autonome, ce qui facilite le déploiement n'importe où. AdminerEvo est disponible pour MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch et MongoDB. De plus, il existe des plugins pour SimpledB, Firebird et Clickhouse. AdminerEvo est développé par la communauté AdminerEvo et est une continuation du projet Adminer par Jakub Vrána.

**Version incluse :** 4.8.4~ynh1

**Démo :** <https://demo.adminer.org/adminer.php?username=>

## Captures d’écran

![Capture d’écran de Adminer](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://docs.adminerevo.org/>
- Dépôt de code officiel de l’app : <https://github.com/adminerevo/adminerevo>
- YunoHost Store : <https://apps.yunohost.org/app/adminer>
- Signaler un bug : <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
ou
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
