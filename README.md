# CI-Tools composer meta package
[![Latest Stable Version](https://poser.pugx.org/sandrokeil/citools/v/stable.png)](https://packagist.org/packages/sandrokeil/citools)
[![Dependency Status](https://www.versioneye.com/user/projects/534ee6aafe0d07a8e10003e3/badge.png)](https://www.versioneye.com/user/projects/534ee6aafe0d07a8e10003e3)
[![Total Downloads](https://poser.pugx.org/sandrokeil/citools/downloads.png)](https://packagist.org/packages/sandrokeil/easy-config)
[![License](https://poser.pugx.org/sandrokeil/citools/license.png)](https://packagist.org/packages/sandrokeil/citools)

The composer.json contains definitions of qa tools for [travis-ci](https://travis-ci.org/),
[coveralls](https://coveralls.io/) and [scrutenizer](https://scrutinizer-ci.com/) integration. So it's really easy to
integrate these tools.

## Installation

Installation of this module uses composer. For composer documentation, please refer to
[getcomposer.org](http://getcomposer.org/).

Put the following into your composer.json

    {
        "require-dev": {
            "sandrokeil/citools": "~1.0"
        }
    }

## Documentation

See [.travis.yml](https://github.com/sandrokeil/qatools/tree/master/.travis.yml),
[.scrutenizer.yml](https://github.com/sandrokeil/qatools/tree/master/.scrutenizer.yml) and [phpunit.xml.dist](https://github.com/sandrokeil/qatools/tree/master/phpunit.xml.dist) for an example configuration.

## Integrated tools

* phpunit/phpunit
* phpunit/php-invoker
* phpunit/phpunit-story
* phpmd/phpmd
* squizlabs/php_codesniffer
* satooshi/php-coveralls
