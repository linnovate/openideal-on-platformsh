# OpenideaL for Platform.sh

This template builds OpenideaL using the [linnovate/openideal-composer](https://github.com/linnovate/openideal-composer) template. The Drupal installer will skip asking for database credentials as they are already provided.

Features:
* PHP 7.4
* MariaDB 10.4
* Drush included
* Composer-based build

## Update repository:

* Diff `composer.json` with https://github.com/linnovate/openideal/blob/3.x/composer.json
* `COMPOSER_MEMORY_LIMIT=-1 composer require [diffed packages from above command]`
* `COMPOSER_MEMORY_LIMIT=-1 composer update --with-dependencies`
* Test
* git commit and push
