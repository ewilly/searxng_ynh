<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# SearXNG for YunoHost

[![Integration level](https://dash.yunohost.org/integration/searxng.svg)](https://dash.yunohost.org/appci/app/searxng) ![Working status](https://ci-apps.yunohost.org/ci/badges/searxng.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/searxng.maintain.svg)

[![Install SearXNG with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=searxng)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install SearXNG quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

SearxXNG is a free internet metasearch engine which aggregates results from more than 70 search services. Users are neither tracked nor profiled.


**Shipped version:** 2023.09.15.19.33.23~ynh1

**Demo:** https://searx.be/

## Screenshots

![Screenshot of SearXNG](./doc/screenshots/screenshot_1.png)

## Disclaimers / important information

Please note that this application is a rolling-release (i.e. each commit is a release) and thus is updated very regularly. People not updating frequently may encounter some bugs or disruptions due to the very nature of this software.

## Documentation and resources

* Official app website: <https://docs.searxng.org/>
* Official user documentation: <https://docs.searxng.org/user/>
* Official admin documentation: <https://docs.searxng.org/admin/>
* Upstream app code repository: <https://github.com/searxng/searxng>
* YunoHost documentation for this app: <https://yunohost.org/app_searxng>
* Report a bug: <https://github.com/YunoHost-Apps/searxng_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/searxng_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/searxng_ynh/tree/testing --debug
or
sudo yunohost app upgrade searxng -u https://github.com/YunoHost-Apps/searxng_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
