# npmtest-mversion

#### basic test coverage for  [mversion (v1.10.1)](https://github.com/mikaelbr/mversion#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mversion.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mversion) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mversion.svg)](https://travis-ci.org/npmtest/node-npmtest-mversion)

#### A cross packaging manager module version handler/bumper

[![NPM](https://nodei.co/npm/mversion.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mversion)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mversion/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mversion/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mversion/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mversion/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mversion/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mversion/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mversion/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mversion/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mversion/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mversion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mversion/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mversion/build/test-report.html](https://npmtest.github.io/node-npmtest-mversion/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mversion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mversion/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mversion/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mversion/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mversion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mversion/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mversion/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mversion/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikael Brevik",
        "url": "@mikaelbrevik"
    },
    "bin": {
        "mversion": "./bin/version"
    },
    "bugs": {
        "url": "https://github.com/mikaelbr/mversion/issues"
    },
    "dependencies": {
        "chalk": "^0.5.0",
        "cli-usage": "^0.1.2",
        "contra": "^1.6.8",
        "minimatch": "^1.0.0",
        "minimist": "^0.2.0",
        "rc": "^0.5.0",
        "semver": "^4.0.3",
        "through2": "^1.0.0",
        "update-notifier": "^0.2.2",
        "vinyl-fs": "^0.3.4"
    },
    "description": "A cross packaging manager module version handler/bumper",
    "devDependencies": {
        "istanbul": "^0.3.0",
        "mocha": "^2.0.1",
        "vinyl": "^0.2.3"
    },
    "directories": {},
    "dist": {
        "shasum": "9322d1a4f11f6670de0024d1823a32a615a3d40e",
        "tarball": "https://registry.npmjs.org/mversion/-/mversion-1.10.1.tgz"
    },
    "gitHead": "459ac7496b34714864ee5e23a33eaf94c243a141",
    "homepage": "https://github.com/mikaelbr/mversion#readme",
    "keywords": [
        "semver",
        "bower",
        "npm",
        "version"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mikaelb"
        }
    ],
    "name": "mversion",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mikaelbr/mversion.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/.bin/_mocha tests/*_test.js -- -u exports -R spec",
        "test": "mocha tests/*_test.js -R spec"
    },
    "version": "1.10.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
