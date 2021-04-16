# tiny
The tiniest npm module.

[![npm (scoped)](https://img.shields.io/npm/v/@sarahsibert/tiny.svg)](https://www.npmjs.com/package/@sarahsibert/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@sarahsibert/tiny.svg)](https://www.npmjs.com/package/@sarahsibert/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
