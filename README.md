# npmtest-inquirer

#### test coverage for  [inquirer (v3.0.6)](https://github.com/sboudrias/Inquirer.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-inquirer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-inquirer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-inquirer.svg)](https://travis-ci.org/npmtest/node-npmtest-inquirer)

#### A collection of common interactive command line user interfaces.

[![NPM](https://nodei.co/npm/inquirer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/inquirer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-inquirer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-inquirer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-inquirer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-inquirer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-inquirer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-inquirer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-inquirer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-inquirer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-inquirer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-inquirer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-inquirer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-inquirer/build/test-report.html](https://npmtest.github.io/node-npmtest-inquirer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-inquirer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-inquirer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-inquirer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-inquirer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inquirer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inquirer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-inquirer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-inquirer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Simon Boudrias"
    },
    "bugs": {
        "url": "https://github.com/sboudrias/Inquirer.js/issues"
    },
    "dependencies": {
        "ansi-escapes": "^1.1.0",
        "chalk": "^1.0.0",
        "cli-cursor": "^2.1.0",
        "cli-width": "^2.0.0",
        "external-editor": "^2.0.1",
        "figures": "^2.0.0",
        "lodash": "^4.3.0",
        "mute-stream": "0.0.7",
        "run-async": "^2.2.0",
        "rx": "^4.1.0",
        "string-width": "^2.0.0",
        "strip-ansi": "^3.0.0",
        "through": "^2.3.6"
    },
    "description": "A collection of common interactive command line user interfaces.",
    "devDependencies": {
        "chai": "^3.0.0",
        "cmdify": "^0.0.4",
        "eslint": "^3.10.2",
        "eslint-config-xo-space": "^0.15.0",
        "gulp": "^3.9.0",
        "gulp-coveralls": "^0.1.0",
        "gulp-eslint": "^3.0.1",
        "gulp-exclude-gitignore": "^1.0.0",
        "gulp-istanbul": "^1.1.1",
        "gulp-line-ending-corrector": "^1.0.1",
        "gulp-mocha": "^3.0.0",
        "gulp-nsp": "^2.1.0",
        "gulp-plumber": "^1.0.0",
        "mocha": "^3.1.2",
        "mockery": "^2.0.0",
        "sinon": "^1.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e04aaa9d05b7a3cb9b0f407d04375f0447190347",
        "tarball": "https://registry.npmjs.org/inquirer/-/inquirer-3.0.6.tgz"
    },
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "mocha": true
        },
        "rules": {
            "quotes": [
                "error",
                "single"
            ],
            "no-unused-expressions": "off",
            "handle-callback-err": "off",
            "no-eq-null": "off",
            "eqeqeq": [
                "error",
                "allow-null"
            ]
        }
    },
    "files": [
        "lib"
    ],
    "gitHead": "6fa46107c940bc8fb7ff66191538ed54e181e166",
    "homepage": "https://github.com/sboudrias/Inquirer.js#readme",
    "keywords": [
        "command",
        "prompt",
        "stdin",
        "cli",
        "tty",
        "menu"
    ],
    "license": "MIT",
    "main": "lib/inquirer.js",
    "maintainers": [
        {
            "name": "mischah"
        },
        {
            "name": "sboudrias"
        }
    ],
    "name": "inquirer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sboudrias/Inquirer.js.git"
    },
    "scripts": {
        "prepublish": "gulp prepublish",
        "test": "gulp"
    },
    "version": "3.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
