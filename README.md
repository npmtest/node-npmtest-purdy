# npmtest-purdy

#### test coverage for  [purdy (v2.2.1)](https://github.com/danielb2/purdy.js)  [![npm package](https://img.shields.io/npm/v/npmtest-purdy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-purdy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-purdy.svg)](https://travis-ci.org/npmtest/node-npmtest-purdy)

#### Pretty print objects in real purdy colors. Allows clearer visualization of objects than you get from most pretty printers due to colors. It will also print out the complete path to an object, something that's extremly useful for debugging. Purdy will also

[![NPM](https://nodei.co/npm/purdy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/purdy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-purdy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-purdy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-purdy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-purdy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-purdy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-purdy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-purdy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-purdy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-purdy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-purdy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-purdy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-purdy/build/test-report.html](https://npmtest.github.io/node-npmtest-purdy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-purdy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-purdy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-purdy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-purdy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-purdy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-purdy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-purdy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-purdy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Bretoi"
    },
    "bin": {
        "purdy": "bin/purdy.js"
    },
    "bugs": {
        "url": "https://github.com/danielb2/purdy.js/issues"
    },
    "dependencies": {
        "chalk": "0.4.x",
        "hoek": "2.x.x",
        "joi": "6.x.x"
    },
    "description": "Pretty print objects in real purdy colors. Allows clearer visualization of objects than you get from most pretty printers due to colors. It will also print out the complete path to an object, something that's extremly useful for debugging. Purdy will also",
    "devDependencies": {
        "code": "1.x.x",
        "lab": "6.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "76787564da04f8ef7e9672987bf1d21a726699c4",
        "tarball": "https://registry.npmjs.org/purdy/-/purdy-2.2.1.tgz"
    },
    "gitHead": "b7bb68fc7ce56ceb71c3172c269848a34ac7f735",
    "homepage": "https://github.com/danielb2/purdy.js",
    "keywords": [
        "ansi",
        "terminal",
        "colors",
        "pretty",
        "print",
        "color"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "danielb"
        }
    ],
    "name": "purdy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danielb2/purdy.js.git"
    },
    "scripts": {
        "test": "lab -a code -t 100 -v -I Reflect"
    },
    "version": "2.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
