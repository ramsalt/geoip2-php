# geoip2-php

Binary extension file of [libmaxminddb](https://github.com/maxmind/libmaxminddb) for PHP 8.1 based on [MaxMind-DB-Reader-php](https://github.com/maxmind/MaxMind-DB-Reader-php).

## Building a new release

* Update PHP_VERSION and/or MAXMINDDB_VERSION in [makefile.yml](.github/workflows/makefile.yml)
* Commit and push the changes
* Create a new tag (`vn+1`, eg. `v3`)
* The resulting artifact will be named `maxminddb-${PHP_VERSION}-${MAXMINDDB_VERSION}-${refname}.tar.gz`
