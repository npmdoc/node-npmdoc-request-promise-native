# npmdoc-request-promise-native

#### api documentation for  [request-promise-native (v1.0.3)](https://github.com/request/request-promise-native#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-request-promise-native.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-request-promise-native) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-request-promise-native.svg)](https://travis-ci.org/npmdoc/node-npmdoc-request-promise-native)

#### The simplified HTTP request client 'request' with Promise support. Powered by native ES6 promises.

[![NPM](https://nodei.co/npm/request-promise-native.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request-promise-native)

- [https://npmdoc.github.io/node-npmdoc-request-promise-native/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request-promise-native/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request-promise-native/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request-promise-native/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-request-promise-native/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-request-promise-native/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "request-promise-native",
    "version": "1.0.3",
    "description": "The simplified HTTP request client 'request' with Promise support. Powered by native ES6 promises.",
    "keywords": [
        "xhr",
        "http",
        "https",
        "promise",
        "request",
        "then",
        "thenable",
        "native"
    ],
    "main": "./lib/rp.js",
    "scripts": {
        "test": "./node_modules/.bin/gulp ci",
        "test-publish": "./node_modules/.bin/gulp ci-no-cov",
        "publish-please": "publish-please",
        "prepublish": "publish-please guard"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/request/request-promise-native.git"
    },
    "author": "Nicolai Kamenzky (https://github.com/analog-nico)",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/request/request-promise-native/issues"
    },
    "homepage": "https://github.com/request/request-promise-native#readme",
    "engines": {
        "node": ">=0.12.0"
    },
    "dependencies": {
        "request-promise-core": "1.1.1",
        "stealthy-require": "^1.0.0"
    },
    "peerDependencies": {
        "request": "^2.34"
    },
    "devDependencies": {
        "body-parser": "~1.15.2",
        "chai": "~3.5.0",
        "chalk": "~1.1.3",
        "gulp": "~3.9.1",
        "gulp-coveralls": "~0.1.4",
        "gulp-eslint": "~2.1.0",
        "gulp-istanbul": "~1.0.0",
        "gulp-mocha": "~2.2.0",
        "lodash": "~4.13.1",
        "publish-please": "~2.1.4",
        "request": "^2.34.0",
        "rimraf": "~2.5.3",
        "run-sequence": "~1.2.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
