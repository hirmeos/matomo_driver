# Matomo (Piwik) Driver
[![Build Status](https://travis-ci.org/hirmeos/matomo_driver.svg?branch=master)](https://travis-ci.org/hirmeos/matomo_driver) [![Release](https://img.shields.io/github/release/hirmeos/matomo_driver.svg?colorB=58839b)](https://github.com/hirmeos/matomo_driver/releases) [![License](https://img.shields.io/github/license/hirmeos/matomo_driver.svg?colorB=ff0000)](https://github.com/hirmeos/matomo_driver/blob/master/LICENSE)

## Run via crontab
```
0 0 * * 0 docker run --rm --name "matomo_driver" --env-file /path/to/config.env -v matomo_cache:/usr/src/app/cache -v metrics:/usr/src/app/output openbookpublishers/matomo_driver:1
```
