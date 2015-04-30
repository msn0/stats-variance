# Variance [![Build Status](https://travis-ci.org/msn0/stats-variance.svg?branch=master)](http://travis-ci.org/msn0/stats-variance)

> Calculate variance of data.

## Installation

```sh
$ npm install stats-variance
```

## Usage

```js
var variance = require('stats-variance');

var data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

variance.calc(data); // → 8.25
```

### API

#### calc(data)

##### data

Type: `array`

The data to be analysed; an array of numbers.

## License
MIT &copy; [Michał Jezierski](https://pl.linkedin.com/in/jezierskimichal)
