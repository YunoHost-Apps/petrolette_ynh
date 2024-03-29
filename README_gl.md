<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Petrolette para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)

[![Instalar Petrolette con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=petrolette)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Petrolette de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Pétrolette is a news reader that doesn't know you

Pétrolette is fully self-contained, makes no external call whatsoever, and embarks a total of zero tracker or "analysis" tool. Needless to say she is also completely ad-free.

The application has 2 modes 
- multi user : each user store is own config itself.
- mono user : configuration is store locally in the server. Each visitor see the same page. 

For now, there is no any mechanism included for feed protection. Any visitor can modify the feed list.


**Versión proporcionada:** 1.7.0~ynh1

**Demo:** <https://petrolette.space>

## Capturas de pantalla

![Captura de pantalla de Petrolette](./doc/screenshots/petrolette.webp)

## Documentación e recursos

- Web oficial da app: <https://framagit.org/yphil/petrolette>
- Repositorio de orixe do código: <https://framagit.org/yphil/petrolette>
- Tenda YunoHost: <https://apps.yunohost.org/app/petrolette>
- Informar dun problema: <https://github.com/YunoHost-Apps/petrolette_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
ou
sudo yunohost app upgrade petrolette -u https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
