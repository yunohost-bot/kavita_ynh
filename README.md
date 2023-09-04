<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Kavita for YunoHost

[![Integration level](https://dash.yunohost.org/integration/kavita.svg)](https://dash.yunohost.org/appci/app/kavita) ![Working status](https://ci-apps.yunohost.org/ci/badges/kavita.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/kavita.maintain.svg)

[![Install Kavita with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kavita)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Kavita quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Kavita is a fast, feature rich, cross platform reading server. Built with a focus for manga and the goal of being a full solution for all your reading needs. Setup your own server and share your reading collection with your friends and family.

### Features

- Extensive File support
- Manga/Comic Reader
- Book Reader
- User Management and Sharing
- Cross Platform with no dependencies - Everything in the box
- Full-text search to quickly find what you want to read
- Mixed media Libraries - Light Novels and Manga can be right next to each other
- Fast and efficient library scans. Don't perform I/O if the underlying file hasn't changed.
- OPDS-PS Support


**Shipped version:** 0.7.8~ynh1

**Demo:** https://demo.kavitareader.com/

## Screenshots

![Screenshot of Kavita](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <www.kavitareader.com>
* Official admin documentation: <https://wiki.kavitareader.com/en>
* Upstream app code repository: <https://github.com/Kareadita/Kavita>
* YunoHost documentation for this app: <https://yunohost.org/app_kavita>
* Report a bug: <https://github.com/YunoHost-Apps/kavita_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/kavita_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
or
sudo yunohost app upgrade kavita -u https://github.com/YunoHost-Apps/kavita_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
