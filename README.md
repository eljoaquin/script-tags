# script-tags [![NPM version](https://badge.fury.io/js/script-tags.png)](http://badge.fury.io/js/script-tags)

> Parse HTML script tags into JSON.

## Install with [npm](npmjs.org):

```bash
npm i -g script-tags --save-dev
```

## Install with [bower](bower.io):

```bash
bower install script-tags
```

## scripts( html )

* `html`: pass a string of HTML with the script tags to be parsed
* returns an array, an object for each script tag, each with a `attrs` property and a `html` property.

Example:

```js
var scripts = require("script-tags");
console.log(scripts('<script src="bootstrap.js"></script>'));
//=>   [{ "attrs": { "src": "bootstrap.js" }, "html": ""}]
```

See [example](./test/example.json).


## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by Phaser on May 25, 2014._