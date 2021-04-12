# Petrolette for YunoHost

[![Integration level](https://dash.yunohost.org/integration/petrolette.svg)](https://dash.yunohost.org/appci/app/petrolette) ![](https://ci-apps.yunohost.org/ci/badges/petrolette.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/petrolette.maintain.svg)  
[![Install Petrolette with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=petrolette)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Petrolette quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## License

This package is available under the license [GPLv3](https://www.gnu.org/licenses/agpl-3.0.html)

## Overview
Pétrolette is a news reading home page, free. It is immediately usable without registration with the same URL on the desktop or a mobile device.

News feeds are organized into tabs, which can contain an infinite number of columns; everything is configurable, and saved directly in the browser cache. To view the same feeds on your phone, either export / import the petrolette.conf file, or (recommended) use the user's personal cloud synchronization feature.

Petrolette

**Shipped version:** 1.2.5

## Screenshots

![](https://framagit.org/yphil/assets/-/raw/master/img/petrolette.png)

## Demo

* [Official demo](petrolette.space)

## Documentation

 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features
#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/petrolette%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/petrolette/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/petrolette%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/petrolette/)

## Links

 * Report a bug: https://github.com/oiseauroch/petrolette_ynh/issues
 * App website: http://petrolette.space/
 * Upstream app repository: https://framagit.org/yphil/petrolette
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/petrolette/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/Yunohost-Apps/petrolette_ynh/tree/testing --debug
or
sudo yunohost app upgrade petrolette -u https://github.com/Yunohost-Apps/petrolette_ynh/tree/testing --debug
```
