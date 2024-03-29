<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Petrolette per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)

[![Installa Petrolette con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=petrolette)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Petrolette su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Pétrolette is a news reader that doesn't know you

Pétrolette is fully self-contained, makes no external call whatsoever, and embarks a total of zero tracker or "analysis" tool. Needless to say she is also completely ad-free.

The application has 2 modes 
- multi user : each user store is own config itself.
- mono user : configuration is store locally in the server. Each visitor see the same page. 

For now, there is no any mechanism included for feed protection. Any visitor can modify the feed list.


**Versione pubblicata:** 1.7.0~ynh1

**Prova:** <https://petrolette.space>

## Screenshot

![Screenshot di Petrolette](./doc/screenshots/petrolette.webp)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://framagit.org/yphil/petrolette>
- Repository upstream del codice dell’app: <https://framagit.org/yphil/petrolette>
- Store di YunoHost: <https://apps.yunohost.org/app/petrolette>
- Segnala un problema: <https://github.com/YunoHost-Apps/petrolette_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
o
sudo yunohost app upgrade petrolette -u https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
