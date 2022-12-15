# Laravel Shopify App

![Tests](https://github.com/kyon147/laravel-shopify/workflows/Package%20Test/badge.svg?branch=master)
[![codecov](https://codecov.io/gh/kyon147/laravel-shopify/branch/master/graph/badge.svg?token=qqUuLItqJj)](https://codecov.io/gh/kyon147/laravel-shopify)
[![License](https://poser.pugx.org/kyon147/laravel-shopify/license)](https://packagist.org/packages/osiset/laravel-shopify)

----

This is a maintined version of the wonderful but now depricated https://github.com/gnikyt/laravel-shopify/

----

A full-featured Laravel package for aiding in Shopify App development, similar to `shopify_app` for Rails. Works for Laravel 7 and up.

![Screenshot](screenshot.png)
![Screenshot: Billable](screenshot-billable.png)

## Table of Contents

__*__ *Wiki pages*

- [Goals](#goals)
- [Documentation](#documentation)
- [Installation](../../wiki/Installation)*
- [Route List](../../wiki/Route-List)*
- [Usage](../../wiki/Usage)*
- [Changelog](../../wiki/Changelog)*
- [Contributing Guide](CONTRIBUTING.md)
- [LICENSE](#license)

For more information, tutorials, etc., please view the project's [wiki](../../wiki).

## Goals

- [ ] Per User Auth Working
- [ ] Better support for SPA apps using VueJS
- [ ] Getting "Blade" templates working better with Shopify's new auth process???

## Installing this fork.

To use this fork (for as long as it remains a fork, tbd) you need to add this to your `composer.json` file otherwise you will always hit to parent.

````
"repositories": [{
   "type": "vcs",
   "url": "https://github.com/Kyon147/laravel-shopify"
 }],
 ````
 
After you will be able to select the latest version from this package, which I have purposley kept on the same versioning as the parent to make transition easy.

## Documentation

For full resources on this package, see the [wiki](../..//wiki).

## Issue or request?

If you have found a bug or would like to request a feature for discussion, please use the `ISSUE_TEMPLATE` in this repo when creating your issue. Any issue submitted without this template will be closed.

## License

This project is released under the MIT [license](LICENSE).

## Misc

### Repository

#### Contributors

Contributions are always welcome! Contibutors are updated each release, pulled from Github. See [`CONTRIBUTORS.txt`](CONTRIBUTORS.txt).

If you're looking to become a contributor, please see [`CONTRIBUTING.md`](CONTRIBUTING.md).

#### Maintainers

Maintainers are users who manage the repository itself, whether it's managing the issues, assisting in releases, or helping with pull requests.

Currently this repository is maintained by:

- [@osiset](https://github.com/osiset)
- [@kyon147](https://github.com/kyon147)
- [@lucasmichot](https://github.com/lucasmichot)

Looking to become a maintainer? E-mail @osiset directly.

### Special Note

I develop this package in my spare time, with a busy family/work life like many of you! So, I would like to thank everyone who's helped me out from submitting PRs, to assisting on issues, and plain using the package (I hope its useful). Cheers.
