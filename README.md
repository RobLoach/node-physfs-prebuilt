# node-physfs-prebuilt

Provides prebuilt versions of [PhysFS](http://icculus.org/physfs/). When required, will return the path to your platform's version of the PhysFS library.

## Usage

``` javascript
var libphysfs = require('node-physfs-prebuilt')
// => 'node_modules/node-physfs-prebuilt/linux/x64/libphysfs'
