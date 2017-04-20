# npmtest-hapi-mongodb

#### basic test coverage for  hapi-mongodb (v6.2.1)  [![npm package](https://img.shields.io/npm/v/npmtest-hapi-mongodb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hapi-mongodb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hapi-mongodb.svg)](https://travis-ci.org/npmtest/node-npmtest-hapi-mongodb)

#### A simple Hapi MongoDB connection plugin.

[![NPM](https://nodei.co/npm/hapi-mongodb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hapi-mongodb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hapi-mongodb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hapi-mongodb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hapi-mongodb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hapi-mongodb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hapi-mongodb/build/test-report.html](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hapi-mongodb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hapi-mongodb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hapi-mongodb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hapi-mongodb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hapi-mongodb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hapi-mongodb",
    "version": "6.2.1",
    "description": "A simple Hapi MongoDB connection plugin.",
    "main": "lib/index.js",
    "scripts": {
        "test": "lab -M 5000 -t 100 -a code -L"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/Marsup/hapi-mongodb.git"
    },
    "keywords": [
        "hapi",
        "mongodb"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Marsup/hapi-mongodb/issues"
    },
    "dependencies": {
        "async": "2.x.x",
        "joi": "10.x.x",
        "mongodb": "2.x.x"
    },
    "devDependencies": {
        "bluebird": "3.x.x",
        "code": "4.x.x",
        "hapi": ">= 13.x.x",
        "lab": "12.x.x"
    },
    "peerDependencies": {
        "hapi": ">= 13.x.x"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
