# ember-cli-test-helpers

[![Build Status](https://travis-ci.org/toranb/ember-cli-test-helpers.svg?branch=master)](https://travis-ci.org/toranb/ember-cli-test-helpers)
[![NPM Downlaads](https://img.shields.io/npm/dm/ember-cli-test-helpers.svg)](https://www.npmjs.org/package/ember-cli-test-helpers)

## Description
Ember-cli-test-helpers is a collection of test helpers

## Installation
```
# install via npm
$ npm install ember-cli-test-helpers --save-dev
```

## Build
```
$ npm install
$ bower install
$ ember test
```

## Usage
Example usage of helpers can be found in usage-test.js.

The wait for helper waits half a second by default, but you can configure this value.

```js
module.exports = function(/* environment, appConfig */) {
  return {
    APP: {
      defaultWaitForTimeout: 1
    }
  };
};
```

## License

Copyright © 2015 Toran Billups

Licensed under the MIT License
