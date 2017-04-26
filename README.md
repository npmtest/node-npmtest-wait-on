# npmtest-wait-on

#### basic test coverage for  [wait-on (v2.0.2)](https://github.com/jeffbski/wait-on#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-wait-on.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wait-on) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wait-on.svg)](https://travis-ci.org/npmtest/node-npmtest-wait-on)

#### wait-on is a cross platform command line utility and Node.js API which will wait for files, ports, sockets, and http(s) resources to become available

[![NPM](https://nodei.co/npm/wait-on.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wait-on)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wait-on/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wait-on/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wait-on/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wait-on/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wait-on/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-wait-on/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-wait-on/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wait-on/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wait-on/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wait-on/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wait-on/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wait-on/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wait-on/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wait-on/build/test-report.html](https://npmtest.github.io/node-npmtest-wait-on/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wait-on/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wait-on/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wait-on/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wait-on/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wait-on/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wait-on/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wait-on/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wait-on/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Barczewski"
    },
    "bin": {
        "wait-on": "bin/wait-on"
    },
    "bugs": {
        "url": "http://github.com/jeffbski/wait-on/issues"
    },
    "dependencies": {
        "core-js": "^2.4.1",
        "joi": "^9.2.0",
        "minimist": "^1.2.0",
        "request": "^2.78.0",
        "rx": "^4.1.0"
    },
    "description": "wait-on is a cross platform command line utility and Node.js API which will wait for files, ports, sockets, and http(s) resources to become available",
    "devDependencies": {
        "accum": "^0.3.6",
        "expect": "^1.8.0",
        "mocha": "^3.1.2",
        "temp": "^0.8.3"
    },
    "directories": {},
    "dist": {
        "shasum": "0a84fd07024c6fc268cb0eabe585be217aaf2baa",
        "tarball": "https://registry.npmjs.org/wait-on/-/wait-on-2.0.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "7975e56dbc454df3fa2113f2688d62b187e142ae",
    "homepage": "https://github.com/jeffbski/wait-on#readme",
    "keywords": [
        "wait",
        "delay",
        "cli",
        "files",
        "tcp",
        "ports",
        "sockets",
        "http",
        "exist",
        "ready",
        "available",
        "portable",
        "cross-platform",
        "unix",
        "linux",
        "windows",
        "win32",
        "osx"
    ],
    "license": "MIT",
    "main": "lib/wait-on",
    "maintainers": [
        {
            "name": "jeffbski"
        }
    ],
    "name": "wait-on",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/jeffbski/wait-on.git"
    },
    "scripts": {
        "test": "mocha 'test/**/*.mocha.js'"
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
