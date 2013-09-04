# Three.js that works with browserify

# How to use

    $ npm install git://github.com/bjoerge/threejs-node --save
  
Now you can do

```js
var THREE = require("three");
```

### Note on versions numbers.

Three.js use an incrementing revision number instead of semantic versioning. The revision of three corresponds to the
patch level in the semantic versioning scheme. Thus, r60 of Three.js is equivalent to version 0.0.60 / tag #v0.0.60 of
this package.


### Protip: Speedup browserify build with the noparse option

You may want to turn off parsing of three.js to speed up your builds with the `noparse` option
 (see [https://github.com/substack/node-browserify#readme](https://github.com/substack/node-browserify#readme))
   
   
