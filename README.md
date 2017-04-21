# npmtest-fs-readdir-recursive

#### basic test coverage for  [fs-readdir-recursive (v1.0.0)](https://github.com/fs-utils/fs-readdir-recursive#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-fs-readdir-recursive.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fs-readdir-recursive) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fs-readdir-recursive.svg)](https://travis-ci.org/npmtest/node-npmtest-fs-readdir-recursive)

#### Recursively read a directory

[![NPM](https://nodei.co/npm/fs-readdir-recursive.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fs-readdir-recursive)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fs-readdir-recursive/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fs-readdir-recursive/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/test-report.html](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fs-readdir-recursive/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fs-readdir-recursive/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fs-readdir-recursive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fs-readdir-recursive/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fs-readdir-recursive/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/fs-utils/fs-readdir-recursive/issues"
    },
    "dependencies": {},
    "description": "Recursively read a directory",
    "devDependencies": {
        "istanbul": "0",
        "mocha": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "8cd1745c8b4f8a29c8caec392476921ba195f560",
        "tarball": "https://registry.npmjs.org/fs-readdir-recursive/-/fs-readdir-recursive-1.0.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "538e912ef5784029b47d247e2f488a7c426537c9",
    "homepage": "https://github.com/fs-utils/fs-readdir-recursive#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "jongleberry"
        },
        {
            "name": "coderhaoxin"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "swatinem"
        },
        {
            "name": "dead-horse"
        }
    ],
    "name": "fs-readdir-recursive",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/fs-utils/fs-readdir-recursive.git"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
