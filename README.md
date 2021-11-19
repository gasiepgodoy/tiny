# @pasquati/tiny 
![npm](https://img.shields.io/npm/v/@pasquati/tiny) ![npm bundle size](https://img.shields.io/bundlephobia/min/@pasquati/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @pasquati/tiny 
```

## Usage

```js
const tiny = require("@pasquati/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```