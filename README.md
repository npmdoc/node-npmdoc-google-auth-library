# npmdoc-google-auth-library

#### api documentation for  [google-auth-library (v0.10.0)](https://github.com/google/google-auth-library-nodejs#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-google-auth-library.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-google-auth-library) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-google-auth-library.svg)](https://travis-ci.org/npmdoc/node-npmdoc-google-auth-library)

#### Google APIs Authentication Client Library for Node.js

[![NPM](https://nodei.co/npm/google-auth-library.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-auth-library)

- [https://npmdoc.github.io/node-npmdoc-google-auth-library/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-auth-library/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-auth-library/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-auth-library/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-google-auth-library/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-google-auth-library/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Google Inc."
    },
    "bugs": {
        "url": "https://github.com/google/google-auth-library-nodejs/issues"
    },
    "contributors": [
        {
            "name": "Google Inc."
        }
    ],
    "dependencies": {
        "gtoken": "^1.2.1",
        "jws": "^3.1.4",
        "lodash.noop": "^3.0.1",
        "request": "^2.74.0"
    },
    "description": "Google APIs Authentication Client Library for Node.js",
    "devDependencies": {
        "coveralls": "^2.11.15",
        "istanbul": "^0.4.5",
        "jsdoc": "^3.4.3",
        "jshint": "^2.9.4",
        "keypair": "^1.0.0",
        "mocha": "^3.2.0",
        "nock": "^9.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "6e15babee85fd1dd14d8d128a295b6838d52136e",
        "tarball": "https://registry.npmjs.org/google-auth-library/-/google-auth-library-0.10.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "480ab2db4c5818a5b43da61d87e578fc20b494ba",
    "homepage": "https://github.com/google/google-auth-library-nodejs#readme",
    "keywords": [
        "google",
        "api",
        "google apis",
        "client",
        "client library"
    ],
    "license": "Apache-2.0",
    "main": "./lib/auth/googleauth",
    "maintainers": [
        {
            "name": "googleapis-packages"
        },
        {
            "name": "jdobry"
        },
        {
            "name": "murgatroid99"
        },
        {
            "name": "stephenplusplus"
        }
    ],
    "name": "google-auth-library",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/google-auth-library-nodejs.git"
    },
    "scripts": {
        "coverage": "istanbul cover -x 'apis/**' _mocha -- --reporter spec --timeout 4000",
        "coveralls": "istanbul cover -x 'apis/**' _mocha --report lcovonly -- --reporter spec --timeout 4000 && cat coverage/lcov.info | coveralls",
        "generate-docs": "jsdoc -c jsdoc-conf.json ./README.md",
        "lint": "jshint lib test",
        "mocha": "mocha --reporter spec --timeout 4000",
        "prepare": "npm test && npm run lint && npm version patch",
        "test": "npm run lint && npm run coverage"
    },
    "version": "0.10.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
