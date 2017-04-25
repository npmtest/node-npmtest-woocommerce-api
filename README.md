# npmtest-woocommerce-api

#### basic test coverage for  [woocommerce-api (v1.4.2)](https://github.com/woocommerce/wc-api-node#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-woocommerce-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-woocommerce-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-woocommerce-api.svg)](https://travis-ci.org/npmtest/node-npmtest-woocommerce-api)

#### A Node.js wrapper for the WooCommerce REST API

[![NPM](https://nodei.co/npm/woocommerce-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/woocommerce-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-woocommerce-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-woocommerce-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-woocommerce-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-woocommerce-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-woocommerce-api/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-woocommerce-api/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-woocommerce-api/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-woocommerce-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-woocommerce-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-woocommerce-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-woocommerce-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-woocommerce-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-woocommerce-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-woocommerce-api/build/test-report.html](https://npmtest.github.io/node-npmtest-woocommerce-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-woocommerce-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-woocommerce-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-woocommerce-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-woocommerce-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-woocommerce-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-woocommerce-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-woocommerce-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-woocommerce-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Claudio Sanches @ Automattic.com"
    },
    "bugs": {
        "url": "https://github.com/woocommerce/wc-api-node/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.6",
        "oauth-1.0a": "^2.0.0",
        "request": "^2.75.0"
    },
    "description": "A Node.js wrapper for the WooCommerce REST API",
    "devDependencies": {
        "chai": "^3.5.0",
        "istanbul": "^0.4.5",
        "jscs": "^3.0.7",
        "jshint": "^2.9.3",
        "mocha": "^3.1.0",
        "nock": "^8.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fdf7b91e2a7e1108ea007c50e2a7b13d1275c40c",
        "tarball": "https://registry.npmjs.org/woocommerce-api/-/woocommerce-api-1.4.2.tgz"
    },
    "gitHead": "3140f543b9c97ecdc8298ebc683c3dd75192d46a",
    "homepage": "https://github.com/woocommerce/wc-api-node#readme",
    "keywords": [
        "woocommerce",
        "rest-api"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "claudiosmweb"
        }
    ],
    "name": "woocommerce-api",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "http://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/woocommerce/wc-api-node.git"
    },
    "scripts": {
        "checkStyle": "jscs .",
        "lint": "jshint .",
        "posttest": "istanbul check-coverage --statements 85 --branches 70 --functions 100 --lines 90 && rm -rf coverage",
        "pretest": "npm run-script lint && npm run-script checkStyle",
        "test": "istanbul cover ./node_modules/.bin/_mocha test.js"
    },
    "version": "1.4.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
