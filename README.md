<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# MediaWiki for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mediawiki.svg)](https://dash.yunohost.org/appci/app/mediawiki) ![](https://ci-apps.yunohost.org/ci/badges/mediawiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mediawiki.maintain.svg)  
[![Install MediaWiki with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mediawiki)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install MediaWiki quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

MediaWiki is a free and open-source wiki software package written in PHP. It serves as the platform for Wikipedia and the other Wikimedia projects, used by hundreds of millions of people each month. MediaWiki is localised in over 350 languages and its reliability and robust feature set have earned it a large and vibrant community of third-party users and developers.


**Shipped version:** 1.37.2~ynh1

**Demo:** https://www.wikipedia.org/, https://www.mediawiki.org/wiki/Project:Sandbox

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

### Shipped extension versions

* [LDAPAuthentication2](https://www.mediawiki.org/wiki/Extension:LDAPAuthentication2)
* [LDAPAuthorization](https://www.mediawiki.org/wiki/Extension:LDAPAuthorization) (**disabled and unused for now**)
* [LDAPGroups](https://www.mediawiki.org/wiki/Extension:LDAPGroups) (**disabled and unused for now**)
* [LDAPUserInfo](https://www.mediawiki.org/wiki/Extension:LDAPUserInfo) (**disabled and unused for now**)
* [LDAPProvider](https://www.mediawiki.org/wiki/Extension:LDAPProvider)
* [PluggableAuth](https://www.mediawiki.org/wiki/Extension:PluggableAuth)

Some of the extensions are marked as "disabled and unused" because they are not immediately required but are part of the MediaWiki "LDAP Stack" which may be needed in future versions.

#### Multi-users support

* Is LDAP supported?: **yes**
* Is HTTP auth supported?: **no**
* Can the app be used by multiple users?: **yes**

## Documentation and resources

* Official app website: https://www.mediawiki.org
* Official user documentation: https://www.mediawiki.org/wiki/Project:Help
* Official admin documentation: https://www.mediawiki.org/wiki/Documentation
* Upstream app code repository: https://github.com/wikimedia/mediawiki
* YunoHost documentation for this app: https://yunohost.org/app_mediawiki
* Report a bug: https://github.com/YunoHost-Apps/mediawiki_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mediawiki_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mediawiki_ynh/tree/testing --debug
or
sudo yunohost app upgrade mediawiki -u https://github.com/YunoHost-Apps/mediawiki_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps