<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Petrolette para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)

[![Instalar Petrolette con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=petrolette)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarPetrolette rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Pétrolette is a news reader that doesn't know you

Pétrolette is fully self-contained, makes no external call whatsoever, and embarks a total of zero tracker or "analysis" tool. Needless to say she is also completely ad-free.

The application has 2 modes 
- multi user : each user store is own config itself.
- mono user : configuration is store locally in the server. Each visitor see the same page. 

For now, there is no any mechanism included for feed protection. Any visitor can modify the feed list.


**Versión actual:** 1.7.0~ynh1

**Demo:** <https://petrolette.space>

## Capturas

![Captura de Petrolette](./doc/screenshots/petrolette.webp)

## Documentaciones y recursos

- Sitio web oficial: <https://framagit.org/yphil/petrolette>
- Repositorio del código fuente oficial de la aplicación : <https://framagit.org/yphil/petrolette>
- Catálogo YunoHost: <https://apps.yunohost.org/app/petrolette>
- Reportar un error: <https://github.com/YunoHost-Apps/petrolette_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
o
sudo yunohost app upgrade petrolette -u https://github.com/YunoHost-Apps/petrolette_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
