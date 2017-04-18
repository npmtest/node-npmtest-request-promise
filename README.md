# npmtest-request-promise

#### test coverage for  [request-promise (v4.2.0)](https://github.com/request/request-promise#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-request-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-request-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-request-promise.svg)](https://travis-ci.org/npmtest/node-npmtest-request-promise)

#### The simplified HTTP request client 'request' with Promise support. Powered by Bluebird.

[![NPM](https://nodei.co/npm/request-promise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request-promise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-request-promise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-promise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-request-promise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-request-promise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-request-promise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-request-promise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-request-promise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-request-promise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-request-promise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-request-promise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-request-promise/build/test-report.html](https://npmtest.github.io/node-npmtest-request-promise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-request-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-request-promise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-request-promise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request-promise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request-promise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-request-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-request-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolai Kamenzky",
        "url": "https://github.com/analog-nico"
    },
    "bugs": {
        "url": "https://github.com/request/request-promise/issues"
    },
    "dependencies": {
        "bluebird": "^3.5.0",
        "request-promise-core": "1.1.1",
        "stealthy-require": "^1.0.0"
    },
    "description": "The simplified HTTP request client 'request' with Promise support. Powered by Bluebird.",
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
    },
    "directories": {},
    "dist": {
        "shasum": "684f77748d6b4617bee6a4ef4469906e6d074720",
        "tarball": "https://registry.npmjs.org/request-promise/-/request-promise-4.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "b5e06f5657b14d2640acd1aa2c778d330a3afc12",
    "homepage": "https://github.com/request/request-promise#readme",
    "keywords": [
        "xhr",
        "http",
        "https",
        "promise",
        "request",
        "then",
        "thenable",
        "bluebird"
    ],
    "license": "ISC",
    "main": "./lib/rp.js",
    "maintainers": [
        {
            "name": "analog-nico"
        },
        {
            "name": "mikeal"
        },
        {
            "name": "nylen"
        },
        {
            "name": "request"
        },
        {
            "name": "simov"
        },
        {
            "name": "tyabonil"
        }
    ],
    "name": "request-promise",
    "optionalDependencies": {},
    "peerDependencies": {
        "request": "^2.34"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/request/request-promise.git"
    },
    "scripts": {
        "prepublish": "publish-please guard",
        "publish-please": "publish-please",
        "test": "gulp ci",
        "test-publish": "gulp ci-no-cov"
    },
    "version": "4.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
