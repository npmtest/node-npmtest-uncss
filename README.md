# npmtest-uncss

#### basic test coverage for  [uncss (v0.14.1)](https://github.com/giakki/uncss)  [![npm package](https://img.shields.io/npm/v/npmtest-uncss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-uncss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-uncss.svg)](https://travis-ci.org/npmtest/node-npmtest-uncss)

#### Remove unused CSS styles

[![NPM](https://nodei.co/npm/uncss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/uncss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-uncss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-uncss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-uncss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-uncss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-uncss/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-uncss/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-uncss/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-uncss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-uncss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-uncss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-uncss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-uncss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-uncss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-uncss/build/test-report.html](https://npmtest.github.io/node-npmtest-uncss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-uncss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-uncss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-uncss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-uncss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-uncss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-uncss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-uncss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-uncss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Giakki"
    },
    "bin": {
        "uncss": "bin/uncss"
    },
    "bugs": {
        "url": "https://github.com/giakki/uncss/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                "src/lib.js",
                "src/uncss.js",
                "src/utility.js"
            ]
        }
    },
    "dependencies": {
        "async": "^1.5.2",
        "bluebird": "~3.1.5",
        "commander": "~2.9.0",
        "glob": "~6.0.1",
        "is-absolute-url": "~2.0.0",
        "is-html": "~1.0.0",
        "lodash": "~4.0.1",
        "object-assign": "^4.0.1",
        "phridge": "~2.0.0",
        "postcss": "~5.0.14",
        "request": "~2.69.0"
    },
    "description": "Remove unused CSS styles",
    "devDependencies": {
        "chai": "~3.5.0",
        "chai-resemble": "~0.4.1",
        "grunt": "~0.4.5",
        "grunt-eslint": "^18.0.0",
        "grunt-mocha-cov": "~0.4.0",
        "load-grunt-tasks": "~3.4.0",
        "time-grunt": "~1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "baf4b170beae165b33187131d3b1dcd43236984e",
        "tarball": "https://registry.npmjs.org/uncss/-/uncss-0.14.1.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "files": [
        "bin",
        "src",
        "LICENSE.md"
    ],
    "gitHead": "d19b523694fa46205189726c291ac1cfb807f7bf",
    "homepage": "https://github.com/giakki/uncss",
    "keywords": [
        "optimize",
        "optimise",
        "unused",
        "selector",
        "CSS",
        "HTML"
    ],
    "license": "MIT",
    "main": "src/uncss.js",
    "maintainers": [
        {
            "name": "giakki"
        }
    ],
    "name": "uncss",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/giakki/uncss.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "0.14.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
