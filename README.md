# npmtest-express-redis-cache

#### basic test coverage for  [express-redis-cache (v0.5.1)](https://github.com/rv-kip/express-redis-cache#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-redis-cache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-redis-cache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-redis-cache.svg)](https://travis-ci.org/npmtest/node-npmtest-express-redis-cache)

#### A module to make Express interact with Redis (create, get, delete). You can automatically cache all your most popular routes in Redis.

[![NPM](https://nodei.co/npm/express-redis-cache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-redis-cache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-redis-cache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-redis-cache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-redis-cache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-redis-cache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-redis-cache/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-redis-cache/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-redis-cache/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-redis-cache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-redis-cache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-redis-cache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-redis-cache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-redis-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-redis-cache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-redis-cache/build/test-report.html](https://npmtest.github.io/node-npmtest-express-redis-cache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-redis-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-redis-cache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-redis-cache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-redis-cache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-redis-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-redis-cache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-redis-cache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-redis-cache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Francois Vespa",
        "url": "https://github.com/co2-git"
    },
    "bin": {
        "express-redis-cache": "bin/express-redis-cache.js"
    },
    "bugs": {
        "url": "https://github.com/rv-kip/express-redis-cache/issues"
    },
    "config": {
        "prefix": "erc:",
        "type": "text/html"
    },
    "contributors": [
        {
            "name": "faceair",
            "url": "https://github.com/faceair"
        },
        {
            "name": "barwin",
            "url": "https://github.com/barwin"
        },
        {
            "name": "rv-kip",
            "url": "https://github.com/rv-kip"
        },
        {
            "name": "amaurigabriel",
            "url": "https://github.com/amaurigabriel"
        },
        {
            "name": "benmcmeen",
            "url": "https://github.com/benmcmeen"
        },
        {
            "name": "pwmckenna",
            "url": "https://github.com/pwmckenna"
        },
        {
            "name": "ramanpreetnara",
            "url": "https://github.com/ramanpreetnara"
        },
        {
            "name": "mdbox",
            "url": "https://github.com/mdbox"
        }
    ],
    "dependencies": {
        "async": "~1.5.0",
        "colors": "^1.1.2",
        "redis": "^2.4.2"
    },
    "description": "A module to make Express interact with Redis (create, get, delete). You can automatically cache all your most popular routes in Redis.",
    "devDependencies": {
        "body-parser": "~1.14.1",
        "express": "~4.13.3",
        "method-override": "~2.3.5",
        "mocha": "~2.3.4",
        "moment": "^2.10.6",
        "request": "~2.67.0",
        "should": "~8.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "ce3e9522a1a7f61c134766593b0464ff09f87dc1",
        "tarball": "https://registry.npmjs.org/express-redis-cache/-/express-redis-cache-0.5.1.tgz"
    },
    "gitHead": "d473449d8f1b439109f2b5361818986821699ad6",
    "homepage": "https://github.com/rv-kip/express-redis-cache#readme",
    "license": "BSD",
    "main": "index.js",
    "maintainers": [
        {
            "name": "francoisv"
        },
        {
            "name": "rv-kip"
        }
    ],
    "name": "express-redis-cache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rv-kip/express-redis-cache.git"
    },
    "scripts": {
        "test": "mocha --check-leaks -R nyan test"
    },
    "version": "0.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
