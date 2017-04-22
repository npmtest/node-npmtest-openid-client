# npmtest-openid-client

#### basic test coverage for  [openid-client (v1.8.1)](https://github.com/panva/node-openid-client)  [![npm package](https://img.shields.io/npm/v/npmtest-openid-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-openid-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-openid-client.svg)](https://travis-ci.org/npmtest/node-npmtest-openid-client)

#### OpenID Connect Relying Party (RP, Client) implementation for Node.js servers, supports passportjs

[![NPM](https://nodei.co/npm/openid-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/openid-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-openid-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-openid-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-openid-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-openid-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-openid-client/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-openid-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-openid-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-openid-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-openid-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-openid-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-openid-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-openid-client/build/test-report.html](https://npmtest.github.io/node-npmtest-openid-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-openid-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-openid-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-openid-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-openid-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-openid-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-openid-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-openid-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-openid-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Filip Skokan"
    },
    "bugs": {
        "url": "https://github.com/panva/node-openid-client/issues"
    },
    "dependencies": {
        "base64url": "^2.0.0",
        "create-error-class": "^3.0.2",
        "got": "^6.3.0",
        "lodash": "^4.13.1",
        "lru-cache": "^4.0.1",
        "node-jose": "^0.9.4",
        "oidc-token-hash": "^1.0.0",
        "uuid": "^3.0.0"
    },
    "description": "OpenID Connect Relying Party (RP, Client) implementation for Node.js servers, supports passportjs",
    "devDependencies": {
        "chai": "^3.5.0",
        "co-mocha": "^1.1.3",
        "eslint": "^3.0.0",
        "eslint-config-airbnb-base": "^11.0.0",
        "eslint-plugin-import": "^2.0.1",
        "istanbul": "^0.4.4",
        "koa": "^2.2.0",
        "koa-body": "^2.0.0",
        "koa-ejs": "^4.0.0",
        "koa-router": "^7.1.1",
        "koa-session": "^5.0.0",
        "mocha": "^3.0.0",
        "nock": "^9.0.0",
        "readable-mock-req": "^0.2.2",
        "sinon": "^2.1.0",
        "timekeeper": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "640f416f8c3597f46a3da5b31102f9406509381d",
        "tarball": "https://registry.npmjs.org/openid-client/-/openid-client-1.8.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "lib"
    ],
    "gitHead": "3bc13540b6c90f5eb7445b25fa9c24ea41fac358",
    "homepage": "https://github.com/panva/node-openid-client",
    "keywords": [
        "openid",
        "connect",
        "client",
        "relying",
        "party",
        "oidc",
        "auth",
        "authentication",
        "identity",
        "oauth",
        "passport",
        "passportjs",
        "strategy",
        "certified",
        "dynamic",
        "config",
        "basic",
        "hybrid",
        "implicit",
        "oauth2"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "panva"
        }
    ],
    "name": "openid-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/panva/node-openid-client.git"
    },
    "scripts": {
        "coverage": "make coverage",
        "lint": "eslint lib example test",
        "test": "make test"
    },
    "version": "1.8.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
