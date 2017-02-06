#webpack-config-build-info

Inject build information into your [webpack] build.

[![build status](http://img.shields.io/travis/webpack-config/webpack-config-build-info/master.svg?style=flat)](https://travis-ci.org/webpack-config/webpack-config-build-info)
[![coverage](http://img.shields.io/coveralls/webpack-config/webpack-config-build-info/master.svg?style=flat)](https://coveralls.io/github/webpack-config/webpack-config-build-info?branch=master)
[![license](http://img.shields.io/npm/l/webpack-config-build-info.svg?style=flat)](https://www.npmjs.com/package/webpack-config-build-info)
[![version](http://img.shields.io/npm/v/webpack-config-build-info.svg?style=flat)](https://www.npmjs.com/package/webpack-config-build-info)
[![downloads](http://img.shields.io/npm/dm/webpack-config-build-info.svg?style=flat)](https://www.npmjs.com/package/webpack-config-build-info)

## Usage

Install:
```sh
npm install --save webpack-config-build-info
```

Add to your `webpack.config.babel.js`:

```js
import buildInfo from `webpack-config-build-info`;

buildInfo()({
  /* existing webpack configuration */
})
```

[webpack]: https://webpack.github.io
