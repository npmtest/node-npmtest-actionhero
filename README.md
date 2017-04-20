# npmtest-actionhero

#### basic test coverage for  [actionhero (v16.0.5)](http://www.actionherojs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-actionhero.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-actionhero) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-actionhero.svg)](https://travis-ci.org/npmtest/node-npmtest-actionhero)

#### actionhero.js is a multi-transport API Server with integrated cluster capabilities and delayed tasks

[![NPM](https://nodei.co/npm/actionhero.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/actionhero)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-actionhero/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-actionhero/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-actionhero/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-actionhero/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-actionhero/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-actionhero/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-actionhero/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-actionhero/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-actionhero/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-actionhero/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-actionhero/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-actionhero/build/test-report.html](https://npmtest.github.io/node-npmtest-actionhero/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-actionhero/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-actionhero/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-actionhero/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-actionhero/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-actionhero/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-actionhero/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-actionhero/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-actionhero/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan Tahler"
    },
    "bin": {
        "actionhero": "./bin/actionhero"
    },
    "bugs": {
        "url": "https://github.com/actionhero/actionhero/issues"
    },
    "dependencies": {
        "async": "^2.1.4",
        "browser_fingerprint": "^0.1.0",
        "etag": "^1.7.0",
        "fakeredis": "^2.0.0",
        "formidable": "^1.0.17",
        "i18n": "^0.8.3",
        "ioredis": "^2.4.1",
        "is-running": "^2.0.1",
        "mime": "^1.3.4",
        "node-resque": "^4.0.1",
        "optimist": "^0.6.1",
        "primus": "^7.0.0",
        "qs": "^6.0.1",
        "uglify-js": "^2.8.5",
        "uuid": "^3.0.0",
        "winston": "^2.0.0",
        "ws": "^2.0.0"
    },
    "description": "actionhero.js is a multi-transport API Server with integrated cluster capabilities and delayed tasks",
    "devDependencies": {
        "chai": "^3.5.0",
        "cross-env": "^4.0.0",
        "dirty-chai": "^1.2.2",
        "mocha": "^3.2.0",
        "request": "^2.75.0",
        "standard": "^10.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "16e9fa32c0a6da290a6acbe650b685b1fa617b36",
        "tarball": "https://registry.npmjs.org/actionhero/-/actionhero-16.0.5.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "badf4101059320c2637cf3c5acda8fef9f67009b",
    "homepage": "http://www.actionherojs.com",
    "keywords": [
        "api",
        "realtime",
        "socket",
        "http",
        "https",
        "web",
        "game",
        "cluster",
        "soa",
        "action",
        "task",
        "delay",
        "service",
        "tcp"
    ],
    "license": "Apache-2.0",
    "main": "actionhero.js",
    "maintainers": [
        {
            "name": "crrobinson14"
        },
        {
            "name": "davidjairala"
        },
        {
            "name": "evantahler"
        },
        {
            "name": "gcoonrod"
        }
    ],
    "name": "actionhero",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/actionhero/actionhero.git"
    },
    "scripts": {
        "help": "node ./bin/actionhero help",
        "postinstall": "echo 'To generate a new actionhero project, run \"node ./node_modules/.bin/actionhero generate\"'",
        "pretest": "standard",
        "start": "node ./bin/actionhero",
        "test": "cross-env NODE_ENV=test mocha"
    },
    "standard": {
        "ignore": [
            "bin/templates",
            "client"
        ],
        "globals": [
            "describe",
            "before",
            "beforeEach",
            "after",
            "afterEach",
            "it",
            "expect"
        ]
    },
    "version": "16.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
