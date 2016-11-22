# SUIT CSS base for morishitter

[![Build Status](https://travis-ci.org/suitcss/base.svg?branch=master)](https://travis-ci.org/suitcss/base)

Base styles for web applications. Provides a thin layer on top of
[Normalize.css](https://github.com/necolas/normalize.css).

Read more about how to use [SUIT CSS](https://github.com/suitcss/suit/).

Forked from [suitcss/base](https://github.com/suitcss/base/).

## Installation

```
$ npm install morishitter-base
```

## Scripts

Install [Node](http://nodejs.org) (comes with npm).

```
$ npm install
```

To generate a build:

```
$ npm run build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](http://stylelint.io/)

```
$ npm run lint
```

To generate the testing build.

```
$ npm run build-test
```

Basic visual tests are in `test/index.html`.

```
$ npm run format
```

Format CSS code according to the configuration of stylelint.

## Browser support

* Google Chrome
* Firefox
* Safari
* Opera
* Edge
* Internet Explorer 11

## LICENSE

MIT (same as [suitcss/base](https://github.com/suitcss/base))
