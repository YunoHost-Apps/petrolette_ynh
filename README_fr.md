<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Petrolette pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)

[![Installer Petrolette avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=petrolette)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Petrolette rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Pétrolette is a news reader that doesn't know you

Pétrolette is fully self-contained, makes no external call whatsoever, and embarks a total of zero tracker or "analysis" tool. Needless to say she is also completely ad-free.

The application has 2 modes 
- multi user : each user store is own config itself.
- mono user : configuration is store locally in the server. Each visitor see the same page. 

For now, there is no any mechanism included for feed protection. Any visitor can modify the feed list.


**Version incluse :** 1.7.0~ynh1

**Démo :** <https://petrolette.space>

## Captures d’écran

![Capture d’écran de Petrolette](./doc/screenshots/petrolette.webp)

## Documentations et ressources

- Site officiel de l’app : <https://framagit.org/yphil/petrolette>
- Dépôt de code officiel de l’app : <https://framagit.org/yphil/petrolette>
- YunoHost Store : <https://apps.yunohost.org/app/petrolette>
- Signaler un bug : <https://github.com/YunoHost-Apps/petrolette_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
ou
sudo yunohost app upgrade petrolette -u https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
