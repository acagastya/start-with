# start-with

> Determines whether a string begins with the characters of another string, returning `true` or `false` as appropriate.


[![MIT License](https://img.shields.io/badge/license-MIT_License-green.svg?style=flat-square)](https://github.com/bubkoo/start-with/blob/master/LICENSE)

[![build:?](https://img.shields.io/travis/bubkoo/start-with/master.svg?style=flat-square)](https://travis-ci.org/bubkoo/start-with)
[![coverage:?](https://img.shields.io/coveralls/bubkoo/start-with/master.svg?style=flat-square)](https://coveralls.io/github/bubkoo/start-with)


## Install

```
$ npm install --save start-with 
```

## Usage

> For more use-cases see the [tests](https://github.com/bubkoo/start-with/blob/master/test/spec/index.js)

```js
var startWith = require('start-with');

startWith('abcde', 'a');  // => true
startWith('abcde', 'ab'); // => true
startWith('abcde', 'bc'); // => false
startWith('abcde', '');   // => true
startWith('abcde');       // => false
startWith('abcde', null); // => false

```

## Related

- [end-with](https://github.com/bubkoo/end-with) - Determines whether a string ends with the characters of another string, returning `true` or `false` as appropriate.


## Contributing
 
Pull requests and stars are always welcome. 

For bugs and feature requests, please [create an issue](https://github.com/bubkoo/start-with/issues).
   
But before doing anything, please read the [CONTRIBUTING](https://github.com/tunnckocore/starts-with/blob/master/CONTRIBUTING.md) guidelines.
