# tiny
Tiny npm module </br>
![npm (scoped)](https://img.shields.io/npm/v/@mich31/tiny)
![npm bundle size](https://img.shields.io/bundlephobia/min/tiny)
</br>
Removes all spaces from a string.

## Install

```
$ npm install @mich31/tiny
```

## Usage

```js
const tiny = require("@mich31/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```