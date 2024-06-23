<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Petrolette YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)

[![Instalatu Petrolette YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=petrolette)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Petrolette YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Pétrolette is a news reader that doesn't know you

Pétrolette is fully self-contained, makes no external call whatsoever, and embarks a total of zero tracker or "analysis" tool. Needless to say she is also completely ad-free.

The application has 2 modes 
- multi user : each user store is own config itself.
- mono user : configuration is store locally in the server. Each visitor see the same page. 

For now, there is no any mechanism included for feed protection. Any visitor can modify the feed list.


**Paketatutako bertsioa:** 1.7.0~ynh1

**Demoa:** <https://petrolette.space>

## Pantaila-argazkiak

![Petrolette(r)en pantaila-argazkia](./doc/screenshots/petrolette.webp)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://framagit.org/yphil/petrolette>
- Jatorrizko aplikazioaren kode-gordailua: <https://framagit.org/yphil/petrolette>
- YunoHost Denda: <https://apps.yunohost.org/app/petrolette>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/petrolette_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
edo
sudo yunohost app upgrade petrolette -u https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
