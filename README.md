# npmtest-notie

#### test coverage for  [notie (v4.3.0)](https://jaredreich.com/projects/notie)  [![npm package](https://img.shields.io/npm/v/npmtest-notie.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-notie) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-notie.svg)](https://travis-ci.org/npmtest/node-npmtest-notie)

#### notie - a clean and simple notification, input, and selection suite for javascript, with no dependencies

[![NPM](https://nodei.co/npm/notie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/notie)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-notie/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-notie/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-notie/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-notie/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-notie/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-notie/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-notie/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-notie/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-notie/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-notie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-notie/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-notie/build/test-report.html](https://npmtest.github.io/node-npmtest-notie/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-notie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-notie/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-notie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-notie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-notie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-notie/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-notie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-notie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Reich"
    },
    "bugs": {
        "url": "https://github.com/jaredreich/notie/issues"
    },
    "dependencies": {},
    "description": "notie - a clean and simple notification, input, and selection suite for javascript, with no dependencies",
    "devDependencies": {
        "babel-core": "6.23.1",
        "babel-loader": "6.3.2",
        "babel-preset-es2015": "6.22.0",
        "babel-preset-stage-0": "6.22.0",
        "del": "2.2.2",
        "eslint-config-jared": "latest",
        "gulp": "3.9.1",
        "gulp-cssnano": "2.1.2",
        "gulp-rename": "1.2.2",
        "gulp-sass": "3.1.0",
        "gulp-webpack": "1.5.0",
        "run-sequence": "1.2.2",
        "webpack": "2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e805c64c7045ff29532714fad7a658f36464b37c",
        "tarball": "https://registry.npmjs.org/notie/-/notie-4.3.0.tgz"
    },
    "files": [
        "dist/",
        "src/"
    ],
    "gitHead": "9d3d2025fe926cead52077fd115f57cbb0b5ea9b",
    "homepage": "https://jaredreich.com/projects/notie",
    "keywords": [
        "javascript",
        "notification",
        "alert",
        "prompt",
        "confirm",
        "growl",
        "toast",
        "message"
    ],
    "license": "MIT",
    "main": "./dist/notie.min.js",
    "maintainers": [
        {
            "name": "jaredreich"
        }
    ],
    "name": "notie",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jaredreich/notie.git"
    },
    "scripts": {
        "build": "gulp clean && gulp script && gulp style",
        "dev": "gulp"
    },
    "version": "4.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
