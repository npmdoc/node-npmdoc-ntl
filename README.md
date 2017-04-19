# npmdoc-ntl

#### api documentation for  [ntl (v1.2.0)](https://github.com/ruyadorno/ntl#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-ntl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ntl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ntl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ntl)

#### Npm Task List: Interactive cli menu to list/run npm tasks

[![NPM](https://nodei.co/npm/ntl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ntl)

- [https://npmdoc.github.io/node-npmdoc-ntl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ntl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ntl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ntl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ntl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ntl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ruy Adorno",
        "url": "http://ruyadorno.com"
    },
    "ava": {
        "files": [
            "test/index.js"
        ],
        "tap": true,
        "verbose": true
    },
    "bin": {
        "ntl": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/ruyadorno/ntl/issues"
    },
    "dependencies": {
        "inquirer": "^0.12.0",
        "minimist": "^1.2.0",
        "pkginfo": "~0.3.1"
    },
    "description": "Npm Task List: Interactive cli menu to list/run npm tasks",
    "devDependencies": {
        "ava": "^0.11.0",
        "tempdir": "^1.0.0",
        "tempfile": "^1.1.1",
        "xo": "^0.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "40ae664e04e607f7d04b1b5f609c0b831e6914a3",
        "tarball": "https://registry.npmjs.org/ntl/-/ntl-1.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "cli.js"
    ],
    "gitHead": "bcac2d31da966cb2a1f8a474c553317c174aa4e6",
    "homepage": "https://github.com/ruyadorno/ntl#readme",
    "keywords": [
        "npm",
        "task",
        "list",
        "interactive",
        "inquirer",
        "cli-app",
        "cli",
        "ntl",
        "runner",
        "menu"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ruyadorno"
        }
    ],
    "name": "ntl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ruyadorno/ntl.git"
    },
    "scripts": {
        "pretest": "xo",
        "test": "ava"
    },
    "version": "1.2.0",
    "xo": {
        "rules": {
            "consistent-return": 0
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
