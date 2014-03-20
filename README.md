# Graphosaurus

A three-dimensional static graph viewer.

## Build

1. Install [node](http://nodejs.org/), [npm](https://www.npmjs.org/), and [grunt-cli](https://www.npmjs.org/package/grunt-cli)
2. Clone the graphosaurus repository
3. Run `git submodule update --init` to download [almond](https://github.com/jrburke/almond)
4. Run `npm install` to install all the build requirements
4. Run `grunt compile` to build graphosaurus to `dist/`

## Third party libraries

* `lib/tracking-controls`
 * Used for graph movement/controls
 * Taken from [mrdoob/three.js](https://github.com/mrdoob/three.js/blob/master/examples/js/controls/TrackballControls.js)
 * [License](https://github.com/mrdoob/three.js/blob/master/LICENSE)

## Mascot

![gryposaurus](https://upload.wikimedia.org/wikipedia/commons/7/70/Gryposaurus-notabilis_jconway.png)

[John Conway](https://en.wikipedia.org/wiki/User:John.Conway)'s illustration of our glorious leader, the ~~[gryposaurus](https://en.wikipedia.org/wiki/gryposaurus)~~ graphosaurus.
