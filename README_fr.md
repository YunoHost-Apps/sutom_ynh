# Sutom pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/sutom.svg)](https://dash.yunohost.org/appci/app/sutom) ![](https://ci-apps.yunohost.org/ci/badges/sutom.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/sutom.maintain.svg)  
[![Installer Sutom avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sutom)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Sutom rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Jeu de lettres en ligne (et en français) basé sur Wordle. Le jeu se trouve à l'adresse https://sutom.nocle.fr


**Version incluse :** 1.0.0~ynh2

**Démo :** https://sutom.nocle.fr/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://sutom.nocle.fr/
* Dépôt de code officiel de l'app : https://framagit.org/JonathanMM/sutom
* Documentation YunoHost pour cette app : https://yunohost.org/app_sutom
* Signaler un bug : https://github.com/YunoHost-Apps/sutom_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/sutom_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/sutom_ynh/tree/testing --debug
ou
sudo yunohost app upgrade sutom -u https://github.com/YunoHost-Apps/sutom_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps