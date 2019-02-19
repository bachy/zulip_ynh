# Usage of this package (REMOVE THIS SECTION BEFORE RELEASE)
- Copy this app before working on it.
- Edit `conf/nginx.conf` file to match application prerequisites.
- Edit `manifest.json` with application specific information.
- Edit the `install`, `upgrade`, `remove`, `backup`, and `restore` scripts.
- Add a `LICENSE` file for the package.
- Edit `README.md` and README_fr.md.

# Zulip app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/zulip.svg)](https://dash.yunohost.org/appci/app/zulip)
[![Install zulip with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=zulip)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install zulip quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Zulip combines the immediacy of real-time chat with an email threading model.
With Zulip, you can catch up on important conversations while ignoring irrelevant ones.

**Shipped version:** 1.0

## Screenshots

![](https://zulipchat.com/static/images/features/message-formatting.png)

## Demo

* [Official demo](https://chat.zulip.org/login/)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/zulip%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/zulip/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/zulip%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/zulip/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/zulip%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/zulip/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

**More information on the documentation page:**
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/zulip_ynh/issues
 * App website: Link to the official website of this app
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/zulip_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/zulip_ynh/tree/testing --debug
or
sudo yunohost app upgrade zulip -u https://github.com/YunoHost-Apps/zulip_ynh/tree/testing --debug
```
