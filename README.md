# babel-preset-resultsdm

[![npm version](https://badge.fury.io/js/babel-preset-resultsdm.svg)](http://badge.fury.io/js/babel-preset-resultsdm)

Results Driven Marketing's Babel preset for transforming JavaScript.

## Install

```sh
$ npm install --save-dev babel-preset-resultsdm
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["resultsdm"]
}
```

### Via CLI

```sh
$ babel script.js --presets resultsdm
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["resultsdm"]
});
```
