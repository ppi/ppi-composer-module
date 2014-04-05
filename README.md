PPI Composer Module
==================

[@php]:     http://php.net/         "PHP: Hypertext Preprocessor"
[@ppi]:     http://ppi.io/          "PPI Framework - The PHP Meta Framework!"
[@composer]: https://github.com/composer/composer  "Dependency Manager for PHP"

[Composer][@composer] module for [PPI2][@ppi].

[![Total Downloads](https://poser.pugx.org/ppi/composer-module/downloads.png)](https://packagist.org/packages/ppi/composer-module)
[![Latest Stable Version](https://poser.pugx.org/ppi/composer-module/v/stable.png)](https://packagist.org/packages/ppi/composer-module)
[![Latest Unstable Version](https://poser.pugx.org/ppi/composer-module/v/unstable.png)](https://packagist.org/packages/ppi/composer-module)
[![Build Status](https://secure.travis-ci.org/ppi/ppi-composer-module.png)](http://travis-ci.org/ppi/ppi-composer-module)
[![License](https://poser.pugx.org/ppi/composer-module/license.png)](https://packagist.org/packages/ppi/composer-module)

Composer
--------

<img src="https://getcomposer.org/img/logo-composer-transparent.png" height="100" />

> Composer helps you declare, manage and install dependencies of PHP projects, ensuring you have the right stack everywhere.
>
> See [https://getcomposer.org/](https://getcomposer.org/) for more information and documentation.

Requirements
------------

* [PHP][@php] 5.3.3 and up
* [PPI Framework 2][@ppi] (2.1.x)

Installation
------------

### 1. Install Composer

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

``` bash
curl -s http://getcomposer.org/installer | php
```

### 2. Add ppi/composer-module to your composer.json and install it

``` bash
$ php composer.phar require ppi/composer-module dev-master
```

Composer will install the module to your project's `vendor/ppi` directory.

### 3. Enable the module

Enable this module by editing `app/config/modules.yml`:

``` yml
modules:
    - PPI\ComposerModule
    # ...
```

License
-------

This module is licensed under the MIT License. See the [LICENSE file](https://github.com/ppi/ppi-composer-module/blob/master/LICENSE) for details.

Authors
-------

* Vítor Brandão - <vitor@ppi.io> ~ [twitter.com/noiselabs](http://twitter.com/noiselabs) ~ [noiselabs.org](http://noiselabs.org)

See also the list of [contributors](https://github.com/ppi/ppi-composer-module/contributors) who participated in this project.

Submitting bugs and feature requests
------------------------------------

Bugs and feature requests are tracked on [GitHub](https://github.com/ppi/ppi-composer-module/issues).

About PPI
---------

<img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Ppi-framework-logo.png" width="74" height="50" />

> PPI is an open source PHP meta-framework. It has taken the good bits from Symfony2, ZendFramework2 & Doctrine2 and combined them together to create a solid and very easy web application framework. It can be considered the boilerplate of PHP frameworks.

