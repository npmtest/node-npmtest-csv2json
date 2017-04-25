# npmtest-csv2json

#### basic test coverage for  [csv2json (v1.3.0)](https://github.com/julien-f/csv2json)  [![npm package](https://img.shields.io/npm/v/npmtest-csv2json.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csv2json) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csv2json.svg)](https://travis-ci.org/npmtest/node-npmtest-csv2json)

#### Stream and CLI to convert CSV to JSON

[![NPM](https://nodei.co/npm/csv2json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csv2json)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csv2json/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv2json/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csv2json/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csv2json/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csv2json/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-csv2json/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-csv2json/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csv2json/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csv2json/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-csv2json/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-csv2json/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv2json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-csv2json/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-csv2json/build/test-report.html](https://npmtest.github.io/node-npmtest-csv2json/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-csv2json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csv2json/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-csv2json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csv2json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csv2json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csv2json/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csv2json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csv2json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julien Fontanet"
    },
    "bin": {
        "csv2json": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/julien-f/csv2json/issues"
    },
    "dependencies": {
        "csv-parser": "^1.11.0",
        "event-to-promise": "^0.7.0",
        "exec-promise": "^0.6.1",
        "husky": "^0.13.1",
        "minimist": "^1.2.0",
        "pump": "^1.0.2",
        "pumpify": "^1.3.5",
        "strip-bom-stream": "^3.0.0",
        "through2": "^2.0.3"
    },
    "description": "Stream and CLI to convert CSV to JSON",
    "devDependencies": {
        "dependency-check": "^2.8.0",
        "jest": "^19.0.2",
        "standard": "^8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6fc823fc6f9d36b3dd195da5fe4906799d56cde8",
        "tarball": "https://registry.npmjs.org/csv2json/-/csv2json-1.3.0.tgz"
    },
    "files": [
        "*.js"
    ],
    "gitHead": "4f504c6b7a0f5e43f277fab5dd7d0b196f15fb80",
    "homepage": "https://github.com/julien-f/csv2json",
    "jest": {
        "testRegex": "\\.spec\\.js$"
    },
    "keywords": [
        "csv",
        "json",
        "csv2json",
        "csvtojson",
        "stream"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "jackhq"
        },
        {
            "name": "julien-f"
        },
        {
            "name": "twilson63"
        }
    ],
    "name": "csv2json",
    "optionalDependencies": {},
    "preferGlobal": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/julien-f/csv2json.git"
    },
    "scripts": {
        "commitmsg": "yarn test",
        "posttest": "standard && dependency-check ./package.json",
        "test": "jest"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
