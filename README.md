# test coverage for  [gulp-inline-source (v3.1.0)](https://github.com/fmal/gulp-inline-source#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-inline-source.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-inline-source) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-inline-source.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-inline-source)
#### Inline flagged js & css sources.

[![NPM](https://nodei.co/npm/gulp-inline-source.png?downloads=true)](https://www.npmjs.com/package/gulp-inline-source)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-inline-source/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-inline-source/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-inline-source/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-gulp-inline-source%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-gulp-inline-source%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-inline-source/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-inline-source/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Filip Malinowski",
        "email": "filip@fmal.me"
    },
    "bugs": {
        "url": "https://github.com/fmal/gulp-inline-source/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "gulp-util": "~3.0.6",
        "inline-source": "~5.2.1",
        "through2": "~2.0.0"
    },
    "description": "Inline flagged js & css sources.",
    "devDependencies": {
        "commitizen": "^2.9.6",
        "cz-conventional-changelog": "^2.0.0",
        "faucet": "0.0.1",
        "husky": "^0.13.3",
        "semantic-release": "^6.3.2",
        "tape": "^4.0.1",
        "validate-commit-msg": "^2.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "fe7b94a3105d3523356ab4e639112fcb2cbfea52",
        "tarball": "https://registry.npmjs.org/gulp-inline-source/-/gulp-inline-source-3.1.0.tgz"
    },
    "gitHead": "029107b8bb75ad09ec295f6fee07ae85b64c1f21",
    "homepage": "https://github.com/fmal/gulp-inline-source#readme",
    "keywords": [
        "gulpplugin",
        "inline",
        "css",
        "javascript"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fmal",
            "email": "fmalinowski@gmail.com"
        }
    ],
    "name": "gulp-inline-source",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/fmal/gulp-inline-source.git"
    },
    "scripts": {
        "commit": "git-cz",
        "commitmsg": "validate-commit-msg",
        "prepush": "npm test",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "tape test/*.js | faucet"
    },
    "version": "3.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
