# css-unit-converter [![Build Status][ci-img]][ci]

Converts CSS values from one unit to another

[PostCSS]: https://github.com/postcss/css-unit-converter
[ci-img]:  https://travis-ci.org/andyjansson/css-unit-converter.svg
[ci]:      https://travis-ci.org/andyjansson/css-unit-converter


## Installation

```js
npm install css-unit-converter
```

## Usage


```js
var convert = require('css-unit-converter');
//convert 1 inch to pc
convert(1, 'in', 'pc'); // 6

//convert 10px to cm with a maximum of 10 decimals
convert(10, 'px', 'cm', 10); // 0.2645833333
```

## Supported Conversions
#### length
From `px` to `px`, `cm`, `mm`, `in`, `pt`, `pc`  
From `cm` to `px`, `cm`, `mm`, `in`, `pt`, `pc`   
From `mm` to `px`, `cm`, `mm`, `in`, `pt`, `pc`       
From `in` to `px`, `cm`, `mm`, `in`, `pt`, `pc`  
From `pt` to `px`, `cm`, `mm`, `in`, `pt`, `pc`  
From `pc` to `px`, `cm`, `mm`, `in`, `pt`, `pc`  
#### angle
From `deg` to `deg`, `grad`, `rad`, `turn`  
From `grad` to `deg`, `grad`, `rad`, `turn`  
From `rad` to `deg`, `grad`, `rad`, `turn`  
From `turn` to `deg`, `grad`, `rad`, `turn`  
#### time
From `s` to `s`, `ms`  
From `ms` to `s`, `ms`  
#### frequency
From `Hz` to `Hz`, `kHz`  
From `kHz` to `Hz`, `kHz`  
#### resolution
From `dpi` to `dpi`, `dpcm`, `dppx`  
From `dpcm` to `dpi`, `dpcm`, `dppx`  
From `dppx` to `dpi`, `dpcm`, `dppx`  
