[![npm (scoped)](https://img.shields.io/npm/v/@marvizusd/tiny.svg)](https://github.com/marvizusd/tiny)
[![install size](https://packagephobia.now.sh/badge?p=@marvizusd/tiny)](https://packagephobia.now.sh/result?p=@marvizusd/tiny)
@marvizusd/tiny

Removes all spaces from a string.

## Install

```
$ npm install @marvizusd/tiny
```

## Usage

```js
const tiny = require("@marvizusd/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
