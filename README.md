# npmtest-through

#### basic test coverage for  [through (v2.3.8)](https://github.com/dominictarr/through)  [![npm package](https://img.shields.io/npm/v/npmtest-through.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-through) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-through.svg)](https://travis-ci.org/npmtest/node-npmtest-through)

#### simplified stream construction

[![NPM](https://nodei.co/npm/through.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/through)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-through/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-through/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-through/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-through/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-through/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-through/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-through/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-through/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-through/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-through/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-through/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-through/build/test-report.html](https://npmtest.github.io/node-npmtest-through/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-through/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-through/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-through/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-through/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-through/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-through/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-through/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-through/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "dominictarr.com"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/through/issues"
    },
    "dependencies": {},
    "description": "simplified stream construction",
    "devDependencies": {
        "from": "~0.1.3",
        "stream-spec": "~0.3.5",
        "tape": "~2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "0dd4c9ffaabc357960b1b724115d7e0e86a2e1f5",
        "tarball": "https://registry.npmjs.org/through/-/through-2.3.8.tgz"
    },
    "gitHead": "2c5a6f9a0cc54da759b6e10964f2081c358e49dc",
    "homepage": "https://github.com/dominictarr/through",
    "keywords": [
        "stream",
        "streams",
        "user-streams",
        "pipe"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "through",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dominictarr/through.git"
    },
    "scripts": {
        "test": "set -e; for t in test/*.js; do node $t; done"
    },
    "testling": {
        "browsers": [
            "ie/8..latest",
            "ff/15..latest",
            "chrome/20..latest",
            "safari/5.1..latest"
        ],
        "files": "test/*.js"
    },
    "version": "2.3.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
