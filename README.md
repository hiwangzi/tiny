# @zill057/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@zill057/tiny)](https://github.com/zill057/tiny)
[![npm bundle size(minified)](https://img.shields.io/bundlephobia/min/@zill057/tiny)](https://github.com/zill057/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @zill057/tiny
```

## Usage

```js
const tiny = require("@zill057/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

## Reference

[How to make a beautiful, tiny npm package and publish it](https://www.freecodecamp.org/news/how-to-make-a-beautiful-tiny-npm-package-and-publish-it-2881d4307f78/)
