# npmtest-glob

#### basic test coverage for  [glob (v7.1.1)](https://github.com/isaacs/node-glob#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-glob.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-glob) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-glob.svg)](https://travis-ci.org/npmtest/node-npmtest-glob)

#### a little globber

[![NPM](https://nodei.co/npm/glob.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/glob)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-glob/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-glob/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-glob/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-glob/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-glob/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-glob/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-glob/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-glob/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-glob/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-glob/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-glob/build/test-report.html](https://npmtest.github.io/node-npmtest-glob/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-glob/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-glob/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-glob/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-glob/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-glob/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-glob/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-glob/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-glob/build/screenCapture.npmPackageDependencyTree.svg)



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
        "minimatch": "^3.0.2",
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
        "shasum": "805211df04faaf1c63a3600306cdf5ade50b2ec8",
        "tarball": "https://registry.npmjs.org/glob/-/glob-7.1.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "files": [
        "glob.js",
        "sync.js",
        "common.js"
    ],
    "gitHead": "bc8d43b736a98a9e289fdfceee9266cff35e5742",
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
    "version": "7.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
