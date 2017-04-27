# npmtest-jsdom

#### basic test coverage for  [jsdom (v10.0.0)](https://github.com/tmpvar/jsdom#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jsdom.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsdom) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsdom.svg)](https://travis-ci.org/npmtest/node-npmtest-jsdom)

#### A JavaScript implementation of many web standards

[![NPM](https://nodei.co/npm/jsdom.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsdom)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsdom/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsdom/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsdom/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsdom/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsdom/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jsdom/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jsdom/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsdom/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsdom/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsdom/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsdom/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsdom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsdom/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsdom/build/test-report.html](https://npmtest.github.io/node-npmtest-jsdom/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsdom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsdom/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsdom/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsdom/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsdom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsdom/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsdom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsdom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "canvas": false,
        "vm": "./lib/jsdom/vm-shim.js"
    },
    "bugs": {
        "url": "https://github.com/tmpvar/jsdom/issues"
    },
    "dependencies": {
        "abab": "^1.0.3",
        "acorn": "^4.0.4",
        "acorn-globals": "^3.1.0",
        "array-equal": "^1.0.0",
        "content-type-parser": "^1.0.1",
        "cssom": ">= 0.3.2 < 0.4.0",
        "cssstyle": ">= 0.2.37 < 0.3.0",
        "escodegen": "^1.6.1",
        "html-encoding-sniffer": "^1.0.1",
        "nwmatcher": ">= 1.3.9 < 2.0.0",
        "parse5": "^1.5.1",
        "pn": "^1.0.0",
        "request": "^2.79.0",
        "request-promise-native": "^1.0.3",
        "sax": "^1.2.1",
        "symbol-tree": "^3.2.1",
        "tough-cookie": "^2.3.2",
        "webidl-conversions": "^4.0.0",
        "whatwg-encoding": "^1.0.1",
        "whatwg-url": "^4.3.0",
        "xml-name-validator": "^2.0.1"
    },
    "description": "A JavaScript implementation of many web standards",
    "devDependencies": {
        "benchmark": "1.0.0",
        "browserify": "^14.0.0",
        "chai": "^3.5.0",
        "colors": "^1.1.2",
        "ecstatic": "^2.1.0",
        "eslint": "^3.14.1",
        "eslint-plugin-html": "^2.0.0",
        "fs-readdir-recursive": "^1.0.0",
        "karma": "^1.4.1",
        "karma-browserify": "^5.1.1",
        "karma-chrome-launcher": "^2.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-webworker": "^1.3.0",
        "karma-sauce-launcher": "^1.1.0",
        "mocha": "^3.2.0",
        "mocha-sugar-free": "^1.3.1",
        "nodeunit": "0.10.2",
        "optimist": "0.6.1",
        "portfinder": "^1.0.13",
        "q": "^1.4.1",
        "selenium-standalone": "^6.0.1",
        "server-destroy": "^1.0.1",
        "st": "^1.2.0",
        "watchify": "^3.9.0",
        "wd": "^1.1.3",
        "webidl2js": "^5.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3dda0b760aa248dd9b1392f8bb82e93ad70377b4",
        "tarball": "https://registry.npmjs.org/jsdom/-/jsdom-10.0.0.tgz"
    },
    "gitHead": "50ebb593deb1b6c344b1a3c4c2e215b9a09f2fe2",
    "homepage": "https://github.com/tmpvar/jsdom#readme",
    "keywords": [
        "dom",
        "html",
        "whatwg",
        "w3c"
    ],
    "license": "MIT",
    "main": "./lib/api.js",
    "maintainers": [
        {
            "name": "tmpvar"
        },
        {
            "name": "domenic"
        },
        {
            "name": "sebmaster"
        }
    ],
    "name": "jsdom",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tmpvar/jsdom.git"
    },
    "scripts": {
        "benchmark": "node ./benchmark/runner",
        "benchmark-browser": "node ./benchmark/runner --bundle",
        "convert-idl": "node ./scripts/webidl/convert",
        "lint": "eslint . && eslint test/web-platform-tests/to-upstream --ext .html",
        "prepublish": "npm run convert-idl",
        "pretest": "npm run convert-idl && git submodule update --init --recursive",
        "test": "npm run test-mocha-all && npm run test-old",
        "test-api": "mocha test/api",
        "test-browser": "npm run test-karma && npm run test-karma-worker && npm run test-browser-old",
        "test-browser-old": "node ./test/browser-runner",
        "test-karma": "karma start test/karma.conf.js",
        "test-karma-worker": "karma start test/karma-webworker.conf.js",
        "test-mocha": "mocha",
        "test-mocha-all": "mocha test/index.js",
        "test-old": "node ./test/runner",
        "test-tuwpt": "mocha test/web-platform-tests/to-upstream.js",
        "test-wpt": "mocha test/web-platform-tests/index.js",
        "update-authors": "git log --format=\"%aN <%aE>\" | sort -f | uniq > AUTHORS.txt"
    },
    "version": "10.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
