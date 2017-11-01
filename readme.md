Data Cacher
===========

[![build status](https://img.shields.io/travis/magsdk/data-cacher.svg?style=flat-square)](https://travis-ci.org/magsdk/data-cacher)
[![npm version](https://img.shields.io/npm/v/mag-data-cacher.svg?style=flat-square)](https://www.npmjs.com/package/mag-data-cacher)
[![dependencies status](https://img.shields.io/david/magsdk/data-cacher.svg?style=flat-square)](https://david-dm.org/magsdk/data-cacher)
[![devDependencies status](https://img.shields.io/david/dev/magsdk/data-cacher.svg?style=flat-square)](https://david-dm.org/magsdk/data-cacher?type=dev)
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

If you have any problems or suggestions please open an [issue](https://github.com/magsdk/data-cacher/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`mag-data-cacher` is released under the [MIT License](license.md).
