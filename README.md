# npmtest-koa-redis

#### basic test coverage for  [koa-redis (v3.0.0)](https://github.com/koajs/koa-redis)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-redis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-redis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-redis.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-redis)

#### koa session with redis using koa-generic-session

[![NPM](https://nodei.co/npm/koa-redis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-redis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-redis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-redis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-redis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-redis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-redis/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-koa-redis/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-koa-redis/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-redis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-redis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-redis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-redis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-redis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-redis/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-redis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-redis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-redis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-redis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-redis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-redis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-redis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "dead_horse"
    },
    "bugs": {
        "url": "https://github.com/koajs/koa-redis/issues"
    },
    "dependencies": {
        "co-redis": "^2.1.1",
        "co-wrap-all": "^1.0.0",
        "debug": "^2.6.3",
        "hiredis": "~0.5.0",
        "redis": "^2.7.1"
    },
    "description": "koa session with redis using koa-generic-session",
    "devDependencies": {
        "autod": "^2.8.0",
        "co-mocha": "^1.2.0",
        "connect": "^3.6.0",
        "connect-redis": "^3.2.0",
        "istanbul": "^0.4.5",
        "koa": "^1.2.4",
        "koa-generic-session": "^1.11.5",
        "mocha": "^3.2.0",
        "should": "^11.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a683778408eb80bd22f8317fdc5b1473cbf7b7e3",
        "tarball": "https://registry.npmjs.org/koa-redis/-/koa-redis-3.0.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "7e4940ab0dd930756e21a600f6d1a010ea4b799a",
    "homepage": "https://github.com/koajs/koa-redis",
    "keywords": [
        "koa",
        "middleware",
        "session",
        "redis"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "daawesomep"
        },
        {
            "name": "dead_horse"
        }
    ],
    "name": "koa-redis",
    "optionalDependencies": {
        "hiredis": "~0.5.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/koa-redis.git"
    },
    "scripts": {
        "autod": "autod -w --prefix=^ --keep=koa -D co-mocha,mocha,istanbul,autod",
        "test": "istanbul cover node_modules/mocha/bin/_mocha -- --require co-mocha \"test/**/*.test.js\"",
        "test-only": "mocha --require co-mocha \"test/**/*.test.js\""
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
