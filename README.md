# npmdoc-eazy-logger

#### api documentation for  [eazy-logger (v3.0.2)](https://github.com/shakyshane/easy-logger)  [![npm package](https://img.shields.io/npm/v/npmdoc-eazy-logger.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eazy-logger) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eazy-logger.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eazy-logger)

#### Simple cli logger

[![NPM](https://nodei.co/npm/eazy-logger.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eazy-logger)

- [https://npmdoc.github.io/node-npmdoc-eazy-logger/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Shane Osbourne"
    },
    "bugs": {
        "url": "https://github.com/shakyshane/easy-logger/issues"
    },
    "dependencies": {
        "tfunk": "^3.0.1"
    },
    "description": "Simple cli logger",
    "devDependencies": {
        "chai": "^3.5.0",
        "chalk": "^1.1.1",
        "coveralls": "^2.11.2",
        "jshint": "^2.6.0",
        "lodash-cli": "4.12.0",
        "mocha": "^2.1.0",
        "sinon": "^1.12.2"
    },
    "directories": {},
    "dist": {
        "shasum": "a325aa5e53d13a2225889b2ac4113b2b9636f4fc",
        "tarball": "https://registry.npmjs.org/eazy-logger/-/eazy-logger-3.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "index.js",
        "lodash.custom.js",
        "example.js"
    ],
    "gitHead": "8724cc93039c67ef4a7ec17b1e6ad05c69323bfe",
    "homepage": "https://github.com/shakyshane/easy-logger",
    "keywords": [
        "plugins"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "https://github.com/shakyshane/easy-logger/blob/master/LICENSE"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "shakyshane"
        }
    ],
    "name": "eazy-logger",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shakyshane/easy-logger.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "lint": "jshint index.js test/*.js",
        "lodash": "lodash include=cloneDeep,merge exports=node",
        "test": "npm run lint && mocha"
    },
    "version": "3.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
