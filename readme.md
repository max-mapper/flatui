# flatui

a version of flatui that can be require()'d with npm and used with browserify

## installation

```
npm install --save flatui
```

## usage

```
var flatui = require('flatui')
// flatui is the entire flatui css stylesheet w/ inline base64 images
```

you can use various CSS loader modules to insert it into your page, e.g.:

### [defaultcss](http://npmjs.org/defaultcss)

```
var defaultcss = require('defaultcss')
defaultcss('flatui', require('flatui'))
```

### [insert-css](http://npmjs.org/insert-css)

```
var insertCSS = require('insert-css')
insertCSS(require('flatui'))
```

## building

```
npm install
npm run build
```
