# npmtest-eslint-plugin-import

#### test coverage for  [eslint-plugin-import (v2.2.0)](https://github.com/benmosher/eslint-plugin-import)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-import.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-import) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-import.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-import)

#### Import with sanity.

[![NPM](https://nodei.co/npm/eslint-plugin-import.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-import)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-import/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-import/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-import/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-import/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-import/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-import/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-import/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Mosher"
    },
    "bugs": {
        "url": "https://github.com/benmosher/eslint-plugin-import/issues"
    },
    "dependencies": {
        "builtin-modules": "^1.1.1",
        "contains-path": "^0.1.0",
        "debug": "^2.2.0",
        "doctrine": "1.5.0",
        "eslint-import-resolver-node": "^0.2.0",
        "eslint-module-utils": "^2.0.0",
        "has": "^1.0.1",
        "lodash.cond": "^4.3.0",
        "minimatch": "^3.0.3",
        "pkg-up": "^1.0.0"
    },
    "description": "Import with sanity.",
    "devDependencies": {
        "babel-eslint": "next",
        "babel-plugin-istanbul": "^2.0.1",
        "babel-preset-es2015-argon": "latest",
        "babel-register": "6.16.3",
        "chai": "^3.4.0",
        "coveralls": "^2.11.4",
        "cross-env": "^3.1.0",
        "eslint": "3.x",
        "eslint-import-resolver-node": "file:./resolvers/node",
        "eslint-import-resolver-webpack": "file:./resolvers/webpack",
        "eslint-module-utils": "file:./utils",
        "eslint-plugin-import": "2.x",
        "gulp": "^3.9.0",
        "gulp-babel": "6.1.2",
        "istanbul": "^0.4.0",
        "linklocal": "^2.6.0",
        "mocha": "^3.1.2",
        "nyc": "^8.3.0",
        "redux": "^3.0.4",
        "rimraf": "2.5.2",
        "typescript": "^2.0.3",
        "typescript-eslint-parser": "^0.4.0"
    },
    "directories": {
        "test": "tests"
    },
    "dist": {
        "shasum": "72ba306fad305d67c4816348a4699a4229ac8b4e",
        "tarball": "https://registry.npmjs.org/eslint-plugin-import/-/eslint-plugin-import-2.2.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "lib",
        "config",
        "memo-parser"
    ],
    "gitHead": "90ef48b3ade57c77526b285f75dc0cfc41537831",
    "homepage": "https://github.com/benmosher/eslint-plugin-import",
    "keywords": [
        "eslint",
        "eslintplugin",
        "es6",
        "jsnext",
        "modules",
        "import",
        "export"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "benmosher"
        }
    ],
    "name": "eslint-plugin-import",
    "nyc": {
        "require": [
            "babel-register"
        ],
        "sourceMap": false,
        "instrument": false
    },
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "2.x - 3.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/benmosher/eslint-plugin-import.git"
    },
    "scripts": {
        "ci-test": "eslint ./src && gulp pretest && cross-env NODE_PATH=./lib istanbul cover --report lcovonly --dir reports/coverage _mocha tests/lib/ -- --recursive --reporter dot",
        "cover": "gulp pretest && cross-env NODE_PATH=./lib istanbul cover --dir reports/coverage _mocha tests/lib/ -- --recursive -R progress",
        "coverage-report": "npm t && nyc report --reporter html",
        "coveralls": "nyc report --reporter lcovonly && cat ./coverage/lcov.info | coveralls",
        "debug": "cross-env NODE_PATH=./lib mocha debug --recursive --reporter dot tests/lib/",
        "posttest": "eslint ./src",
        "prepublish": "gulp prepublish",
        "pretest": "linklocal",
        "test": "cross-env BABEL_ENV=test NODE_PATH=./src nyc -s mocha -R dot --recursive tests/src -t 5s",
        "test-all": "npm test && for resolver in ./resolvers/*; do cd $resolver && npm test && cd ../..; done",
        "test-compiled": "npm run prepublish && NODE_PATH=./lib mocha --compilers js:babel-register --recursive tests/src",
        "watch": "cross-env NODE_PATH=./src mocha --watch --compilers js:babel-register --recursive tests/src"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
