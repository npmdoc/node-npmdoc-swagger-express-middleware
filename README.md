# npmdoc-swagger-express-middleware

#### api documentation for  [swagger-express-middleware (v1.0.0-alpha.12)](https://github.com/BigstickCarpet/swagger-express-middleware)  [![npm package](https://img.shields.io/npm/v/npmdoc-swagger-express-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-swagger-express-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-swagger-express-middleware.svg)](https://travis-ci.org/npmdoc/node-npmdoc-swagger-express-middleware)

#### Swagger middleware and mocks for Express

[![NPM](https://nodei.co/npm/swagger-express-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger-express-middleware)

- [https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-swagger-express-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Messinger",
        "url": "http://jamesmessinger.com"
    },
    "bugs": {
        "url": "https://github.com/BigstickCarpet/swagger-express-middleware/issues"
    },
    "dependencies": {
        "body-parser": "^1.13.3",
        "cookie-parser": "^1.3.5",
        "debug": "^2.2.0",
        "lodash": "^3.10.1",
        "mkdirp": "^0.5.1",
        "multer": "^0.1.8",
        "ono": "^1.0.22",
        "swagger-methods": "^1.0.0",
        "swagger-parser": ">=3.0.0-alpha.8",
        "tmp": "0.0.27",
        "tv4": "^1.2.5",
        "type-is": "^1.6.8"
    },
    "description": "Swagger middleware and mocks for Express",
    "devDependencies": {
        "basic-auth": "^1.0.3",
        "chai": "^3.2.0",
        "chai-datetime": "^1.4.0",
        "coveralls": "^2.11.4",
        "express": "^4.13.3",
        "istanbul": "^0.3.19",
        "jscs": "^2.1.1",
        "jshint": "^2.8.0",
        "mocha": "^2.3.2",
        "npm-check-updates": "^2.2.0",
        "sinon": "^1.16.1",
        "supertest": "^1.1.0",
        "version-bump-prompt": "^1.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3e9ecbcb3fc34c9cbfe04afb8b788f1e6d5ab360",
        "tarball": "https://registry.npmjs.org/swagger-express-middleware/-/swagger-express-middleware-1.0.0-alpha.12.tgz"
    },
    "engines": {
        "node": ">=0.10.36",
        "npm": ">=2.0"
    },
    "gitHead": "eb417f90d211cbcf9864345cfebbb9c1ec84fd45",
    "homepage": "https://github.com/BigstickCarpet/swagger-express-middleware",
    "keywords": [
        "express",
        "swagger",
        "middleware",
        "mock",
        "fake",
        "stub",
        "rest",
        "api",
        "json"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "bigstickcarpet"
        },
        {
            "name": "rkrauskopf"
        }
    ],
    "name": "swagger-express-middleware",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "4.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/BigstickCarpet/swagger-express-middleware.git"
    },
    "scripts": {
        "build": "npm run lint",
        "bump": "bump --prerelease --tag --push --all",
        "istanbul": "istanbul cover _mocha --dir coverage/node -- --bail --recursive tests/fixtures tests/specs",
        "lint": "jshint . --verbose && jscs . --verbose",
        "mocha": "mocha --bail --recursive tests/fixtures tests/specs",
        "release": "npm run upgrade && npm run build && npm test && npm run bump && npm publish",
        "start": "cd samples && node sample2.js",
        "test": "npm run istanbul",
        "upgrade": "ncu \"/(!multer)/\" --upgradeAll && npm update"
    },
    "version": "1.0.0-alpha.12",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
