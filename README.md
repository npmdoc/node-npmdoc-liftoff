# api documentation for  [liftoff (v2.3.0)](https://github.com/js-cli/js-liftoff)  [![npm package](https://img.shields.io/npm/v/npmdoc-liftoff.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-liftoff) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-liftoff.svg)](https://travis-ci.org/npmdoc/node-npmdoc-liftoff)
#### Launch your command line tool with ease.

[![NPM](https://nodei.co/npm/liftoff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/liftoff)

[![apidoc](https://npmdoc.github.io/node-npmdoc-liftoff/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-liftoff/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-liftoff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-liftoff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tyler Kellen",
        "url": "http://goingslowly.com/"
    },
    "bugs": {
        "url": "https://github.com/js-cli/js-liftoff/issues"
    },
    "dependencies": {
        "extend": "^3.0.0",
        "findup-sync": "^0.4.2",
        "fined": "^1.0.1",
        "flagged-respawn": "^0.3.2",
        "lodash.isplainobject": "^4.0.4",
        "lodash.isstring": "^4.0.1",
        "lodash.mapvalues": "^4.4.0",
        "rechoir": "^0.6.2",
        "resolve": "^1.1.7"
    },
    "description": "Launch your command line tool with ease.",
    "devDependencies": {
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "istanbul": "^0.4.3",
        "jscs": "^2.11.0",
        "jshint": "^2.9.2",
        "mocha": "^2.4.5",
        "sinon": "~1.17.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a98f2ff67183d8ba7cfaca10548bd7ff0550b385",
        "tarball": "https://registry.npmjs.org/liftoff/-/liftoff-2.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "gitHead": "be40ec3a3fa5854b4ab496a97f3d5877bf747b0b",
    "homepage": "https://github.com/js-cli/js-liftoff",
    "keywords": [
        "command line"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert"
        },
        {
            "name": "phated"
        },
        {
            "name": "tkellen"
        },
        {
            "name": "tusbar"
        }
    ],
    "name": "liftoff",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/js-cli/js-liftoff.git"
    },
    "scripts": {
        "test": "jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index"
    },
    "version": "2.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module liftoff](#apidoc.module.liftoff)
1.  [function <span class="apidocSignatureSpan"></span>liftoff (opts)](#apidoc.element.liftoff.liftoff)
1.  [function <span class="apidocSignatureSpan">liftoff.</span>super_ ()](#apidoc.element.liftoff.super_)
1.  [function <span class="apidocSignatureSpan">liftoff.</span>toString ()](#apidoc.element.liftoff.toString)



# <a name="apidoc.module.liftoff"></a>[module liftoff](#apidoc.module.liftoff)

#### <a name="apidoc.element.liftoff.liftoff"></a>[function <span class="apidocSignatureSpan"></span>liftoff (opts)](#apidoc.element.liftoff.liftoff)
- description and source-code
```javascript
function Liftoff(opts) {
  EE.call(this);
  extend(this, parseOptions(opts));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.liftoff.super_"></a>[function <span class="apidocSignatureSpan">liftoff.</span>super_ ()](#apidoc.element.liftoff.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.liftoff.toString"></a>[function <span class="apidocSignatureSpan">liftoff.</span>toString ()](#apidoc.element.liftoff.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
