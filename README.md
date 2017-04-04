# api documentation for  [express-subdomain (v1.0.5)](https://github.com/bmullan91/express-subdomain#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-subdomain.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-subdomain) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-subdomain.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-subdomain)
#### Simple and lightweight middleware to handle subdomains

[![NPM](https://nodei.co/npm/express-subdomain.png?downloads=true)](https://www.npmjs.com/package/express-subdomain)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-subdomain/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-express-subdomain_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-subdomain/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-subdomain/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-subdomain/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian Mullan",
        "email": "bmullan91@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/bmullan91/express-subdomain/issues"
    },
    "dependencies": {},
    "description": "Simple and lightweight middleware to handle subdomains",
    "devDependencies": {
        "chai": "~1.9.1",
        "colors": "~0.6.2",
        "composable-middleware": "^0.3.0",
        "coveralls": "~2.10.0",
        "express": "~4.1.1",
        "istanbul": "~0.2.10",
        "mocha": "~1.18.2",
        "mocha-lcov-reporter": "0.0.1",
        "request": "~2.34.0"
    },
    "directories": {},
    "dist": {
        "shasum": "990ef97940b7f4c2823d9593648b79be858a638b",
        "tarball": "https://registry.npmjs.org/express-subdomain/-/express-subdomain-1.0.5.tgz"
    },
    "gitHead": "66da15d5f08ceca779f35caf076289c5739ff74b",
    "homepage": "https://github.com/bmullan91/express-subdomain#readme",
    "keywords": [
        "express",
        "express-subdomain",
        "subdomain"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bmullan91",
            "email": "bmullan91@gmail.com"
        }
    ],
    "name": "express-subdomain",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/bmullan91/express-subdomain.git"
    },
    "scripts": {
        "coverage": "./test/pre-script.sh; istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage; ./test/post-script.sh",
        "test": "./test/pre-script.sh; ./node_modules/.bin/mocha --reporter spec; ./test/post-script.sh"
    },
    "version": "1.0.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module express-subdomain](#apidoc.module.express-subdomain)



# <a name="apidoc.module.express-subdomain"></a>[module express-subdomain](#apidoc.module.express-subdomain)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
