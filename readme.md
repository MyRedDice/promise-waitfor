<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [promise-waitfor](#promise-waitfor)
- [Documentation](#documentation)
  - [Examples](#examples)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# promise-waitfor

[![NPM](https://nodei.co/npm/promise-waitfor.png)](https://nodei.co/npm/promise-waitfor/)

[![Build Status](https://travis-ci.org/SimonSchick/promise-waitfor.svg?branch=master)](https://travis-ci.org/SimonSchick/promise-waitfor)
[![Dependencies](https://david-dm.org/SimonSchick/promise-waitfor.svg)](https://david-dm.org/SimonSchick/promise-waitfor)
[![npm version](http://img.shields.io/npm/v/promise-waitfor.svg)](https://npmjs.org/package/promise-waitfor)

Just run ```npm install promise-waitfor```

# Documentation

```javascript
Promise waitFor(Function condition, Function predicate = condition, interval int=50)
```

## Examples

```javascript
const waitFor = require('promise-waitfor')(YOUR_PROMISE_CONSTRUCTOR_HERE);

waitFor(CONDITION)
.then(...)

waitFor(CONDITION, VALUEOVERRIDE)
.then(...)

waitFor(CONDITION, VALUEOVERRIDE, TEST_INTERVAL)
.then(...)
```

For now more info check test.js and the index.js for further information.