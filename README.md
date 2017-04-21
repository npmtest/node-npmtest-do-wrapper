# npmtest-do-wrapper

#### basic test coverage for  [do-wrapper (v3.11.1)](https://github.com/matt-major/do-wrapper)  [![npm package](https://img.shields.io/npm/v/npmtest-do-wrapper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-do-wrapper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-do-wrapper.svg)](https://travis-ci.org/npmtest/node-npmtest-do-wrapper)

#### Node.js Wrapper for Digital Ocean API v2

[![NPM](https://nodei.co/npm/do-wrapper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/do-wrapper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-do-wrapper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-do-wrapper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-do-wrapper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-do-wrapper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-do-wrapper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-do-wrapper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-do-wrapper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-do-wrapper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-do-wrapper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-do-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-do-wrapper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-do-wrapper/build/test-report.html](https://npmtest.github.io/node-npmtest-do-wrapper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-do-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-do-wrapper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-do-wrapper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-do-wrapper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-do-wrapper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-do-wrapper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "do-wrapper",
    "version": "3.11.1",
    "description": "Node.js Wrapper for Digital Ocean API v2",
    "author": "Matt Major",
    "homepage": "https://github.com/matt-major/do-wrapper",
    "repository": {
        "type": "git",
        "url": "https://github.com/matt-major/do-wrapper.git"
    },
    "main": "./dist/do-wrapper.js",
    "types": "./types/do-wrapper.d.ts",
    "scripts": {
        "build": "gulp compile && npm run doc",
        "precommit": "npm t",
        "test": "jshint src/*.js && ./node_modules/mocha/bin/mocha",
        "doc": "./node_modules/.bin/jsdoc src/*.js -d docs/"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/matt-major/do-wrapper/issues"
    },
    "keywords": [
        "digital ocean",
        "digitalocean",
        "droplet",
        "cloud",
        "wrapper",
        "api",
        "babel",
        "es6"
    ],
    "dependencies": {
        "request": "2.74.0"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "gulp": "3.9.1",
        "gulp-babel": "5.2.1",
        "gulp-uglify": "1.5.1",
        "husky": "0.10.2",
        "jsdoc": "3.4.0",
        "jsdox": "^0.4.9",
        "jshint": "2.8.0",
        "mocha": "^2.4.5",
        "should": "^8.2.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
