# Category Repository Bugfix
Bugfix for catalog repository cherry picked from https://github.com/magento/magento2/pull/7598.

Installation via composer:

```
composer require "piotrkwiecinski/magento2-module-category-repository-id-bugfix: 0.1.3"
```

Run from Magento 2 root directory:

for enable module:
```
php -f bin/magento module:enable PiotrKwiecinski_CatalogRepositoryIdFix
```

for update system:
```
php -f bin/magento setup:upgrade
```
