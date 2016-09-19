Data Cacher
===========

[![Build Status](https://img.shields.io/travis/magsdk/data-cacher.svg?style=flat-square)](https://travis-ci.org/magsdk/data-cacher)
[![NPM version](https://img.shields.io/npm/v/mag-data-cacher.svg?style=flat-square)](https://www.npmjs.com/package/mag-data-cacher)
[![Dependencies Status](https://img.shields.io/david/magsdk/data-cacher.svg?style=flat-square)](https://david-dm.org/magsdk/data-cacher)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/magsdk)


Caches data in a predetermined range.


## Installation ##

```bash
npm install mag-data-cacher
```


## Usage ##

Add to the scope:

```js
var DataCacher = require('mag-data-cacher');
```

In some event handler:

```js
var DataCacher = require('mag-data-cacher'),
    cacher     = new DataCacher({
        pageSize: 7,
        cacheSize: 2,
        request: {},
        getter: function ( callback, config, count ) {
            //
        }
    });
```


## Contribution ##

If you have any problem or suggestion please open an issue [here](https://github.com/magsdk/data-cacher/issues).
Pull requests are welcomed with respect to the [JavaScript Code Style](https://github.com/DarkPark/jscs).


## License ##

`mag-data-cacher` is released under the [MIT License](license.md).
