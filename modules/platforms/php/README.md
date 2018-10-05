# PHP Thin Client #

## Installation ##

The client requires PHP version 7.2 or higher (http://php.net/manual/en/install.php) and Composer Dependency Manager (https://getcomposer.org/download/).

The client additionally requires PHP Multibyte String extension. Depending on you PHP configuration you may need to additionally install/configure it (http://php.net/manual/en/mbstring.installation.php)

### Installation from the PHP Package Repository ###

Run from your application root
```
composer require apache/apache-ignite-client
```

To use the client in your application, include `vendor/autoload.php` file, generated by Composer, to your source code, eg.
```
require_once __DIR__ . '/vendor/autoload.php';
```

### Installation from Sources ###

1. Download Ignite sources to `local_ignite_path`
2. Go to `local_ignite_path/modules/platforms/php` folder
3. Execute `composer install --no-dev` command

```bash
cd local_ignite_path/modules/platforms/php
composer install --no-dev
```

To use the client in your application, include `vendor/autoload.php` file, generated by Composer, to your source code, eg.
```
require_once "<local_ignite_path>/vendor/autoload.php";
```

For more information, see [Apache Ignite PHP Thin Client documentation](https://apacheignite.readme.io/docs/php-thin-client).