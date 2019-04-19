# Bootstrap extension
[![Latest Stable Version](https://poser.pugx.org/mediawiki/bootstrap/version.png)](https://packagist.org/packages/mediawiki/bootstrap)
[![Packagist download count](https://poser.pugx.org/mediawiki/bootstrap/d/total.png)](https://packagist.org/packages/mediawiki/bootstrap)
[![Dependency Status](https://www.versioneye.com/php/mediawiki:bootstrap/badge.png)](https://www.versioneye.com/php/mediawiki:bootstrap)

The [Bootstrap extension][mw-bootstrap] provides the
[Bootstrap web front-end framework][bootstrap] to skins and extensions.

Currently Bootstrap 4.3.1 is provided.

## Requirements

- PHP 5.6 or later
- MediaWiki 1.27 or later
- [Composer][composer]

## Installation

1. On a command line go to your MediaWiki installation directory

2. With Composer installed, run
   `composer require "mediawiki/bootstrap:~1.0"`
3. __Done:__ Navigate to _Special:Version_ on your wiki to verify that the
   extension is successfully installed.

## Documentation

See the [Bootstrap extension documentation](docs).

It may also be worthwhile to have a look at the [Bootstrap site on
MediaWiki][mw-bootstrap] and the related [talk page][mw-bootstrap-talk]

## License

You can use the Bootstrap extension under the [GNU General Public License,
version 3][license] (or any later version).

[bootstrap]: https://getbootstrap.com
[mw-bootstrap]: https://www.mediawiki.org/wiki/Extension:Bootstrap
[mw-bootstrap-talk]: https://www.mediawiki.org/wiki/Extension_Talk:Bootstrap
[mw-testing]: https://www.mediawiki.org/wiki/Manual:PHP_unit_testing
[composer]: https://getcomposer.org/
[license]: https://www.gnu.org/copyleft/gpl.html
