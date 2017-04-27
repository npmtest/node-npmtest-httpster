# npmtest-httpster

#### basic test coverage for  [httpster (v1.0.3)](https://github.com/SimbCo/httpster#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-httpster.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-httpster) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-httpster.svg)](https://travis-ci.org/npmtest/node-npmtest-httpster)

#### Simple http server for static content

[![NPM](https://nodei.co/npm/httpster.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/httpster)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-httpster/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-httpster/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-httpster/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-httpster/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-httpster/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-httpster/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-httpster/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-httpster/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-httpster/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-httpster/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-httpster/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-httpster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-httpster/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-httpster/build/test-report.html](https://npmtest.github.io/node-npmtest-httpster/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-httpster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-httpster/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-httpster/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-httpster/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-httpster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-httpster/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-httpster/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-httpster/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Simeon Bateman",
        "url": "http://www.simb.net"
    },
    "bin": {
        "httpster": "./bin/httpster"
    },
    "bugs": {
        "url": "https://github.com/SimbCo/httpster/issues"
    },
    "dependencies": {
        "commander": "1.2.x",
        "cors": "2.4.x",
        "express": "3.2.x",
        "node-env-file": "0.1.4",
        "serve-index": "^1.6.0"
    },
    "description": "Simple http server for static content",
    "devDependencies": {
        "coffee-script": "1.6.x",
        "mocha": "~1.11.0",
        "should": "~1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "9430b7a7ddf3112c7b956ce7d99252901e05d83a",
        "tarball": "https://registry.npmjs.org/httpster/-/httpster-1.0.3.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "88ffb3121740fa1c6fa68dc89f2ccfc843bd25a0",
    "homepage": "https://github.com/SimbCo/httpster#readme",
    "keywords": [
        "http",
        "web",
        "server"
    ],
    "license": "MIT",
    "main": "./lib/httpster",
    "maintainers": [
        {
            "name": "simbco"
        }
    ],
    "name": "httpster",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git://github.com/SimbCo/httpster.git"
    },
    "scripts": {
        "prepublish": "coffee -o lib/ src/"
    },
    "version": "1.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
