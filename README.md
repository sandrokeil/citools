# CI-Tools composer meta package for php code

> You want one repository which loads common php qa tools?

> You want examples of all the beautiful services around github for php analysis?

> You want to be a badge poser?

> This module comes to the rescue!

[![Latest Stable Version](https://poser.pugx.org/sandrokeil/citools/v/stable.png)](https://packagist.org/packages/sandrokeil/citools)
[![Dependency Status](https://www.versioneye.com/user/projects/540371b0eab62a132800014a/badge.svg)](https://www.versioneye.com/user/projects/540371b0eab62a132800014a)
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
[.scrutenizer.yml](https://github.com/sandrokeil/qatools/tree/master/.scrutenizer.yml) and
[phpunit.xml.dist](https://github.com/sandrokeil/qatools/tree/master/phpunit.xml.dist) for an example configuration.

## Continuous Integration/Inspection tools
Register your repository on these services for php analysis.

* [travis-ci](https://travis-ci.org/)
* [scrutenizer](https://scrutinizer-ci.com/)
* [coveralls](https://coveralls.io/)
* [VersionEye](https://www.versioneye.com)
* [SensioLabsInsight](https://insight.sensiolabs.com/)

## Integrated libraries
These php libraries are used to generate reports for above services.

* [phpunit/phpunit](https://github.com/sebastianbergmann/phpunit)
* [phpunit/php-invoker](https://github.com/sebastianbergmann/php-invoker)
* [phpmd/phpmd](https://github.com/phpmd/phpmd)
* [squizlabs/php_codesniffer](https://github.com/squizlabs/PHP_CodeSniffer)
* [satooshi/php-coveralls](https://github.com/satooshi/php-coveralls)

## Additional badges
All continuous integration/inspection tools have its own badges but if you want to be a badge poser, here are more.

* [Packagist](https://packagist.org/) - Register your repository here and other services will use it
* [HHVM Status](http://hhvm.h4cc.de) - [HHVM](http://hhvm.com/) support badge
* [Badge Poser](https://poser.pugx.org) - Several badges depending on repository
* [Shields.io](http://shields.io/) - Custom badges
* [Still Maintained](http://stillmaintained.com/) - Finally a place to mark your open source project 
as abandoned or looking for a new maintainer

## Application access
Some ci tools need access to your repository. Sign in with your github login to grant access to your repository. Here
are a list of webhooks and services which needs access to your repository.

### Webhooks
 * https://scrutinizer-ci.com/github-callback (automatically created)
 * https://insight.sensiolabs.com/api/analyze-scm (automatically created)

### Services
 * Packagist (must be created manually, please follow instructions on the website)
 * Travis CI (must be created manually, please follow instructions on the website)
