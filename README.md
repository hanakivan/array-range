# array-range

[![](https://flat.badgen.net/npm/v/@ivanhanak_com/array-range?icon=npm)](https://www.npmjs.com/package/@ivanhanak_com/array-range)
[![NPM Weekly Downloads](https://badgen.net/npm/dw/@ivanhanak_com/array-range)](https://www.npmjs.com/package/@ivanhanak_com/array-range)

Lightweight (0.01kb) library to create an array range.

This library is a bit larger in file size because supports IE11. If you don't need to support this browser, check out the superlightweight **array-range-es6** for modern browsers only (e.g. Safari 13+, EDGE 13+). 

You can find it here [here](https://www.npmjs.com/package/@ivanhanak_com/array-range). 

## Changelog

See the whole [Changelog](/CHANGELOG.md).

## Install

Using npm:

```sh
npm install @ivanhanak_com/array-range
```

Using yarn:

```sh
yarn add @ivanhanak_com/array-range
```

## Import
```javascript
import range from '@ivanhanak_com/array-range';
```

## Usage

```javascript
const rangeItems = range(5); //creates [0,1,2,3,4,5]
```

## Browser support
IE11+