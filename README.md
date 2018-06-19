# npmtest-glob

#### basic test coverage for  [glob (7.1.2)](https://github.com/isaacs/node-glob#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-glob.svg)](https://travis-ci.org/npmtest/node-npmtest-glob)

#### a little globber

[![NPM](https://nodei.co/npm/glob.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/glob)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-glob/tree/alpha)|
|--:|:--|
| coverage : | [![coverage](https://npmtest.github.io/node-npmtest-glob/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-glob/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-glob/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-glob/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-glob/build/app) || build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-glob/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-glob/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html)

[![coverage](https://npmtest.github.io/node-npmtest-glob/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-glob/build/test-report.html](https://npmtest.github.io/node-npmtest-glob/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-glob/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-glob/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-glob/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-glob/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-glob/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-glob/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-glob/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-glob/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me/"
    },
    "bugs": {
        "url": "https://github.com/isaacs/node-glob/issues"
    },
    "dependencies": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.0.4",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
    },
    "description": "a little globber",
    "devDependencies": {
        "mkdirp": "0",
        "rimraf": "^2.2.8",
        "tap": "^7.1.2",
        "tick": "0.0.6"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-MJTUg1kjuLeQCJ+ccE4Vpa6kKVXkPYJ2mOCQyUuKLcLQsdrMCpBPUi8qVE6+YuaJkozeA9NusTAw3hLr8Xe5EQ==",
        "shasum": "c19c9df9a028702d678612384a6552404c636d15",
        "tarball": "https://registry.npmjs.org/glob/-/glob-7.1.2.tgz"
    },
    "engines": {
        "node": "*"
    },
    "files": [
        "glob.js",
        "sync.js",
        "common.js"
    ],
    "gitHead": "8fa8d561e08c9eed1d286c6a35be2cd8123b2fb7",
    "homepage": "https://github.com/isaacs/node-glob#readme",
    "license": "ISC",
    "main": "glob.js",
    "maintainers": [
        {
            "name": "isaacs"
        }
    ],
    "name": "glob",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/isaacs/node-glob.git"
    },
    "scripts": {
        "bench": "bash benchmark.sh",
        "benchclean": "node benchclean.js",
        "prepublish": "npm run benchclean",
        "prof": "bash prof.sh && cat profile.txt",
        "profclean": "rm -f v8.log profile.txt",
        "test": "tap test/*.js --cov",
        "test-regen": "npm run profclean && TEST_REGEN=1 node test/00-setup.js"
    },
    "version": "2018.6.19",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
