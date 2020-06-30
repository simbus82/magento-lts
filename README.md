# OpenMage LTS
Welcome to the **OpenMage LTS** development repository, a community-driven fork of **Magento Community Edition**.


## OpenMage LTS Project Status
<a href="https://travis-ci.org/openmage/magento-lts"><img src="https://travis-ci.org/openmage/magento-lts.svg" alt="OpenMage Build Status"></a> 
<a href="https://packagist.org/packages/openmage/magento-lts"><img src="https://poser.pugx.org/openmage/magento-lts/d/total.svg" alt="OpenMage Total Downloads"></a>
<a href="https://packagist.org/packages/openmage/magento-lts"><img src="https://poser.pugx.org/openmage/magento-lts/license.svg" alt="OpenMage License"></a>


## Why OpenMage LTS

**OpenMage LTS** is designed to benefit Magento community by offering stable platform after <a href="https://www.openmage.org/community/2019/01/20/after-m1-eol.html" target="_blank">Magento 1.x EOL</a> to continue at least 5 years ahead.

* Continued Long-Term Support (LTS) from Magento 1
* Security patches
* Performance optimizations

Please check out our website <a href="https://www.openmage.org/" target="_blank">OpenMage.org</a> for information about how OpenMage LTS allows Magento 1.x EOL merchants to continue running a secure, stable Magento-based platform while remaining PCI compliant.

* [Getting Started](#getting-started)
* [Installation](#installation)
* [Requirements](#requirements)
* [Translations](#translations)
* [Development](#development)
* [Online Communities](#online-communities)
* [Maintainers](#maintainers)
* [License](#license)
* [Copyright](#copyright)


## Getting Started

This repository is the home of **OpenMage LTS**, an **unofficial** community-driven project. It's goal is to be a dependable alternative to the Magento CE official releases which integrates improvements directly from the community while maintaining a high level of backwards compatibility to the official releases.

Though Magento does not follow [Semantic Versioning](http://semver.org/) we aim to provide a workable system for dependency definition. Each Magento `1.<minor>.<revision>` release will get its own branch (named `1.<minor>.<revision>.x`) that will be independently maintained with upstream patches and community bug fixes for as long as it makes sense to do so (based on available resources). For example, Magento version `1.9.3.4` was merged into the `1.9.3.x` branch.


### Note
The branches older than `1.9.3.x` that were created before this strategy came into practice are **not maintained**.


## Installation

Download the latest archive and extract it, clone the repo, or add a composer dependency to your existing project like so:

```json
"openmage/magento-lts": "1.9.4.x"
```

See [more installation informations](https://www.openmage.org/magento-lts/install.html) about OpenMage LTS.


## Requirements

* PHP 7.0+ (PHP 7.3 and OpenSSL extension strongly recommended)
* MySQL 5.6+ (8.0+ Recommended)


## Translations

There are some new or changed tranlations, if you want add them to your locale pack please check:

- `app/locale/en_US/*_LTS.csv`


## Development

It's likely that you've invested more time and money into your Magento-based eCommerce platform than you even want to think about. With your help, we'd like to make sure that investment continues to pay it's dividends.

**Pull requests with unofficial bug fixes and security patches from the community are encouraged and welcome!**

### PhpStorm Factory Helper

This repo includes class maps for the core Magento files in `.phpstorm.meta.php`.
This file is generated using the following commands:

```
$ wget https://files.magerun.net/n98-magerun.phar
$ docker run --rm -u $UID -v $PWD:/var/www/html php:7.0-apache php n98-magerun.phar dev:ide:phpstorm:meta
```

You can add additional meta files in this directory to cover your own project files. See
[PhpStorm advanced metadata](https://www.jetbrains.com/help/phpstorm/ide-advanced-metadata.html)
for more information.


## Online Communities

* [Website](https://www.openmage.org/)
* [Discord](https://discord.gg/EV8aNbU) (maintained by Flyingmana)
* [Twitter](https://twitter.com/OpenMageProject)
* [Facebook](https://www.facebook.com/OpenMage-1374303459372150)
* [Linkedin](https://www.linkedin.com/groups/13655485/)


## Maintainers

* [Lee Saferite](https://github.com/LeeSaferite)
* [David Robinson](https://github.com/drobinson)
* [Daniel Fahlke aka Flyingmana](https://github.com/Flyingmana)
* [Tymoteusz Motylewski](https://github.com/tmotyl)
* [Sven Reichel](https://github.com/sreichel)
* and over other 100 Contributors!


## License

[Open Software License 3.0 (OSL-3.0)](http://opensource.org/licenses/OSL-3.0)


## Copyright
**Magento** and all related logos are either registered trademarks or trademarks of Adobe Inc. in the United States and/or other Countries. Use of such trademarks is under license and does not imply any affiliation, endorsement, or sponsorship by Adobe Inc.

* Copyright (C) 2020 OpenMage
