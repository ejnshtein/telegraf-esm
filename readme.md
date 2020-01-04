# telegraf-esm

[![node](https://img.shields.io/node/v/telegraf-esm.svg?style=flat-square)](https://www.npmjs.com/package/telegraf-esm)

This is [Telegraf](https://telegraf.js.org) wrapper for [ESM modules](https://nodejs.org/api/esm.html) since [Node 13.5](https://nodejs.org/en/blog/release/v13.5.0/)

### Installation

```
$ npm install telegraf-esm
```
or using `yarn`:
```
$ yarn add telegraf-esm
```


### Usage

```js
import Telegraf, { Telegram, Composer, ... } from 'telegraf-esm'

// your beatiful esm code
```

Basically you can just replace `from 'telegraf'` with `from 'telegraf-esm'`.

### But why?

Since Node 13.5, it's required to use `.cjs` file extension for Commonjs support, but it would require to break legacy support for Node 12 and lower where only Commonjs is allowed.
