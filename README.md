# Ops One Managed Server

[![Packagist Version](https://img.shields.io/packagist/v/gilbertsoft/opsone-managed-server)](https://packagist.org/packages/gilbertsoft/opsone-managed-server)
[![Packagist PHP Version Support](https://img.shields.io/packagist/php-v/gilbertsoft/opsone-managed-server)](https://packagist.org/packages/gilbertsoft/opsone-managed-server)
[![GitHub issues](https://img.shields.io/github/issues/gilbertsoft/opsone-managed-server)](https://github.com/gilbertsoft/opsone-managed-server/issues)
[![GitHub forks](https://img.shields.io/github/forks/gilbertsoft/opsone-managed-server)](https://github.com/gilbertsoft/opsone-managed-server/network)
[![GitHub stars](https://img.shields.io/github/stars/gilbertsoft/opsone-managed-server)](https://github.com/gilbertsoft/opsone-managed-server/stargazers)
[![GitHub license](https://img.shields.io/github/license/gilbertsoft/opsone-managed-server)](https://github.com/gilbertsoft/opsone-managed-server/blob/main/LICENSE.md)
[![GitHub build](https://img.shields.io/github/workflow/status/gilbertsoft/opsone-managed-server/Continuous%20Integration%20(CI))](https://github.com/gilbertsoft/opsone-managed-server/actions/workflows/continuous-integration.yml)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](https://github.com/gilbertsoft/opsone-managed-server/blob/main/CODE_OF_CONDUCT.md)

This package replaces the corresponding Symfony polyfills for installed PHP
extensions to avoid installing these unneeded packages for your PHP project
hosted at an Ops One Managed Server.

**Table of contents**:

- [Installation](#installation)
- [Feedback / Bug reports / Contribution](#feedback--bug-reports--contribution)
- [License](#license)

## Installation

Require this package as normal dependency and by providing the desired branch:

```bash
composer require gilbertsoft/opsone-managed-server dev-<branch>
```

To install the package for a Managed Server Version 8 with PHP 8.1 run:

```bash
composer require gilbertsoft/opsone-managed-server dev-server8-php81
```

Please head to the [branches overview](https://github.com/gilbertsoft/opsone-managed-server/branches/all)
to see all supported combinations. If your desired combination is missing, please
create a [feature request](https://github.com/gilbertsoft/opsone-managed-server/issues/new/choose).

If the package is installed as dev requirement, the package won't work as
expected using the install option `--no-dev`.

## Feedback / Bug reports / Contribution

Bug reports, feature requests and pull requests are welcome in the [GitHub
repository](https://github.com/gilbertsoft/opsone-managed-server).

For support questions or other discussions please use the [GitHub Discussions](https://github.com/gilbertsoft/opsone-managed-server/discussions).

## License

This package is licensed under the [MIT License](https://github.com/gilbertsoft/opsone-managed-server/blob/main/LICENSE.md).
