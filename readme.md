# [broccoli](https://github.com/joliss/broccoli)-htmlmin [![Build Status](https://travis-ci.org/sindresorhus/broccoli-htmlmin.png?branch=master)](https://travis-ci.org/sindresorhus/broccoli-htmlmin)

> Minify HTML using [Minimize](https://github.com/Moveo/minimize)

*Issues with the output should be reported on the Minimize [issue tracker](https://github.com/Moveo/minimize/issues).*


## Install

```
npm install --save broccoli-htmlmin
```


## Example

```js
var htmlmin = require('broccoli-htmlmin');
tree = htmlmin(tree, options);
```


## API

### htmlmin(tree, options)

#### options

See the Minimize [options](https://github.com/Moveo/minimize#options).


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
