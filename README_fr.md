# Whiteboard pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)  
[![Installer Whitebophir avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=petrolette)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Petrolette rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

 Pétrolette est une page d'accueil de lecture d'actualités, libre. Elle est immédiatement utilisable sans inscription avec la même URL dans le navigateur du bureau ou celui d'un appareil mobile.

Les flux / sources sont organisés en onglets, qui peuvent contenir un nombre infini de colonnes ; tout est ré-organisable par glisser / déposer, et sauvegardé dans le cache du navigateur, ou dans le nuage.

**Version incluse :** 1.2.5

## Captures d'écran

![](https://framagit.org/yphil/assets/-/raw/master/img/petrolette.png)

## Démo

* [Démo officielle](petrolette.space)

## Documentation

 * Documentation officielle : https://framagit.org/yphil/petrolette

## Caractéristiques spécifiques YunoHost
#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/petrolette%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/petrolette/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/petrolette%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/petrolette/)

## Liens

 * Signaler un bug : https://github.com/oiseauroch/petrolette_ynh/issues
 * Site de l'application : http://petrolette.space
 * Dépôt de l'application principale : https://framagit.org/yphil/petrolette
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche dev](https://github.com/oiseauroch/petrolette/tree/dev).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/oiseauroch/petrolette/tree/dev --debug
ou
sudo yunohost app upgrade whitebophir -u https://github.com/oiseauroch/petrolette_ynh/tree/dev --debug
```
