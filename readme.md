[![M2 Coding Standard](https://github.com/eugene-petrov/magento2-product-description/actions/workflows/coding-standard.yml/badge.svg?branch=main)](https://github.com/eugene-petrov/magento2-product-description/actions/workflows/coding-standard.yml)
[![M2 Mess Detector](https://github.com/eugene-petrov/magento2-product-description/actions/workflows/mess-detector.yml/badge.svg?branch=main)](https://github.com/eugene-petrov/magento2-product-description/actions/workflows/mess-detector.yml)
[![M2 PHPStan](https://github.com/eugene-petrov/magento2-product-description/actions/workflows/phpstan.yml/badge.svg?branch=main)](https://github.com/eugene-petrov/magento2-product-description/actions/workflows/phpstan.yml)

***ReadyToGo_ProductDescription***

_Task:_ move a product description block to product info section

_Before:_
![img](./.readme/img.png)

_After:_
![img_1](./.readme/img_1.png)

**To enable this module execute:**

- `composer require eugene-petrov/magento2-product-description`
or if the cmd above is not working: `composer config repositories.readyToGoProductDescription vcs git@github.com:eugene-petrov/magento2-product-description.git`
- `php bin/magento setup:upgrade`
- `php bin/magento cache:clean`

