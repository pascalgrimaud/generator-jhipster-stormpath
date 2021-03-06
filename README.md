# Stormpath Module for JHipster
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> JHipster module, Stormpath API integration for Authorization

## Introduction

This is a [JHipster](http://jhipster.github.io/) module, that is meant to be used in a JHipster application.

## Prerequisites

This module installs Stormpath's Spring Boot, Spring Security and AngularJS support and configures everything for you.

<img src="https://raw.githubusercontent.com/stormpath/generator-jhipster-stormpath/master/static/yo-jhipster-stormpath.gif" width="800">

You will need a [free Stormpath account](https://api.stormpath.com/register) and API keys installed to use your application after installing this module.

Specifically, this module configures your JHipster application to use the following Stormpath features:

* Login
* Logout
* User Registration
* Forgot Password

Features we hope to add in a future release:

* Change Password
* User Management
* Internationalization

## Installation

As this is a [JHipster](http://jhipster.github.io/) module, we expect you have [JHipster and its related tools already installed](http://jhipster.github.io/installation.html).

This module requires Jhipster version greater than 3.0 in order to work.

```bash
npm install -g generator-jhipster-stormpath
```

Then run the module on a JHipster generated application:

```bash
yo jhipster-stormpath
```

## License

Apache-2.0 © [Stormpath](https://stormpath.com)

[npm-image]: https://img.shields.io/npm/v/generator-jhipster-stormpath.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-stormpath
[travis-image]: https://travis-ci.org/stormpath/generator-jhipster-stormpath.svg?branch=master
[travis-url]: https://travis-ci.org/stormpath/generator-jhipster-stormpath
[daviddm-image]: https://david-dm.org/stormpath/generator-jhipster-stormpath.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/stormpath/generator-jhipster-module
