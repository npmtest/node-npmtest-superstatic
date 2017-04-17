# test coverage for  [superstatic (v4.0.3)](https://github.com/firebase/superstatic#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-superstatic.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-superstatic) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-superstatic.svg)](https://travis-ci.org/npmtest/node-npmtest-superstatic)
#### A static file server for fancy apps

[![NPM](https://nodei.co/npm/superstatic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/superstatic)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-superstatic/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-superstatic/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-superstatic/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-superstatic/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-superstatic/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-superstatic/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-superstatic/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-superstatic/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-superstatic/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-superstatic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-superstatic/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-superstatic/build/test-report.html](https://npmtest.github.io/node-npmtest-superstatic/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-superstatic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-superstatic/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-superstatic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-superstatic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-superstatic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-superstatic/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-superstatic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-superstatic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Firebase",
        "url": "https://www.firebase.com/"
    },
    "bin": {
        "superstatic": "bin/server"
    },
    "bugs": {
        "url": "https://github.com/firebase/superstatic/issues"
    },
    "dependencies": {
        "as-array": "^2.0.0",
        "async": "^1.5.2",
        "basic-auth-connect": "^1.0.0",
        "chalk": "^1.0.0",
        "char-spinner": "^1.0.1",
        "compare-semver": "^1.0.0",
        "compression": "^1.2.2",
        "connect": "^3.3.3",
        "connect-query": "^0.2.0",
        "destroy": "^1.0.3",
        "fast-url-parser": "^1.1.3",
        "fs-extra": "^0.30.0",
        "glob": "^7.0.3",
        "glob-slasher": "^1.0.1",
        "home-dir": "^1.0.0",
        "is-url": "^1.2.1",
        "join-path": "^1.0.0",
        "lodash": "^4.11.2",
        "mime-types": "^2.0.4",
        "minimatch": "^3.0.2",
        "morgan": "^1.5.0",
        "nash": "^2.0.0",
        "on-finished": "^2.2.0",
        "on-headers": "^1.0.0",
        "path-to-regexp": "^1.2.1",
        "router": "^1.0.0",
        "rsvp": "^3.1.0",
        "string-length": "^1.0.0",
        "try-require": "^1.0.0",
        "update-notifier": "^1.0.1"
    },
    "description": "A static file server for fancy apps",
    "devDependencies": {
        "chai": "^3.0.0",
        "chai-as-promised": "^5.1.0",
        "concat-stream": "^1.5.1",
        "eslint": "^2.9.0",
        "istanbul": "^0.4.0",
        "mocha": "^2.0.1",
        "nsp": "^2.4.0",
        "request": "^2.51.0",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0",
        "std-mocks": "^1.0.0",
        "supertest": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a8ca3770a98489711917f3bd16f719ea92d4e686",
        "tarball": "https://registry.npmjs.org/superstatic/-/superstatic-4.0.3.tgz"
    },
    "gitHead": "572e2ad99b5322810b9d9c16b00983942ce189f4",
    "homepage": "https://github.com/firebase/superstatic#readme",
    "keywords": [
        "static",
        "server",
        "firebase",
        "hosting",
        "pushstate",
        "html5",
        "router",
        "file",
        "directory",
        "hash",
        "hashbang"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "scottcorgan"
        },
        {
            "name": "mbleigh"
        }
    ],
    "name": "superstatic",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/firebase/superstatic.git"
    },
    "scripts": {
        "audit": "npm shrinkwrap --dev && nsp check || true && rm npm-shrinkwrap.json",
        "coverage": "istanbul cover --print detail ./node_modules/.bin/_mocha -- test/unit/** test/integration/**",
        "lint": "eslint .",
        "outdated": "npm outdated --depth 0",
        "test": "npm run lint && npm run coverage",
        "test-integration": "mocha test/integration/**",
        "test-unit": "mocha test/unit/**",
        "watch": "mocha -w test/unit/** test/integration/**"
    },
    "version": "4.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
