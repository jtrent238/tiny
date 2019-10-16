# @jtrent238/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@jtrent238/tiny.svg)](https://www.npmjs.com/package/@jtrent238/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@jtrent238/tiny.svg)](https://www.npmjs.com/package/@jtrent238/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @jtrent238/tiny
```

## Usage

```js
const tiny = require("@jtrent238/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```