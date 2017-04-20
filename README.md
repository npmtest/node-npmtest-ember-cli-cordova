# npmtest-ember-cli-cordova

#### basic test coverage for  [ember-cli-cordova (v0.0.19)](https://github.com/poetic/ember-cli-cordova)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-cordova.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-cordova) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-cordova.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-cordova)

#### A tool for creating hybrid apps using a combination of ember-cli and cordova

[![NPM](https://nodei.co/npm/ember-cli-cordova.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-cordova)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-cordova/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-cordova/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-cordova/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-cordova/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-cordova/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-cordova/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-cordova/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-cordova/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Craige"
    },
    "bugs": {
        "url": "https://github.com/poetic/ember-cli-cordova/issues"
    },
    "dependencies": {
        "broccoli-funnel": "^0.2.3",
        "broccoli-merge-trees": "^0.2.1",
        "chalk": "^0.4.0",
        "findup-sync": "^0.1.3",
        "fs-extra": "^0.8.1",
        "lodash": "^2.4.1",
        "pleasant-progress": "^1.0.1",
        "recursive-readdir": "^1.1.1",
        "rsvp": "^3.0.6",
        "underscore.string": "^2.3.3"
    },
    "description": "A tool for creating hybrid apps using a combination of ember-cli and cordova ",
    "devDependencies": {
        "broccoli-asset-rev": "2.0.0",
        "broccoli-ember-hbs-template-compiler": "^1.6.1",
        "chai": "^1.9.1",
        "ember-cli": "0.1.5",
        "ember-cli-ic-ajax": "0.1.1",
        "ember-cli-qunit": "0.1.2",
        "ember-data": "1.0.0-beta.12",
        "glob": "4.0.5",
        "mocha": "^1.20.1",
        "mocha-jshint": "0.0.7",
        "proxyquire": "^1.0.1",
        "qunit-bdd": "github:jakecraige/qunit-bdd#ember-addon",
        "sinon": "^1.11.1",
        "tmp-sync": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7f67209a7efa80ed968278c2dcd1c2ca1561ccc0",
        "tarball": "https://registry.npmjs.org/ember-cli-cordova/-/ember-cli-cordova-0.0.19.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "gitHead": "8ce5b537436ae959c84ccfacfa1bc86d31504fcc",
    "homepage": "https://github.com/poetic/ember-cli-cordova",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "alexblom"
        },
        {
            "name": "bryanh"
        },
        {
            "name": "danielo"
        },
        {
            "name": "jakecraige"
        },
        {
            "name": "poetic"
        },
        {
            "name": "runspired"
        }
    ],
    "name": "ember-cli-cordova",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/poetic/ember-cli-cordova.git"
    },
    "scripts": {
        "ember-test": "ember test",
        "node-test": "mocha --require node-tests/helpers/_helper.js --reporter spec node-tests/**/*-test.js node-tests/**/**/*-test.js",
        "test": "npm run node-test && npm run ember-test"
    },
    "version": "0.0.19"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
