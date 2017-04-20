# npmtest-postal

#### basic test coverage for  [postal (v2.0.5)](http://github.com/postaljs/postal.js)  [![npm package](https://img.shields.io/npm/v/npmtest-postal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postal.svg)](https://travis-ci.org/npmtest/node-npmtest-postal)

#### Pub/Sub library providing wildcard subscriptions, complex message handling, etc.  Works server and client-side.

[![NPM](https://nodei.co/npm/postal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postal/build/test-report.html](https://npmtest.github.io/node-npmtest-postal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jim Cowart",
        "url": "http://ifandelse.com"
    },
    "bugs": {
        "url": "http://github.com/postaljs/postal.js/issues"
    },
    "contributors": [
        {
            "name": "Jim Cowart",
            "url": "http://ifandelse.com"
        },
        {
            "name": "Alex Robson",
            "url": "http://nerdventure.io"
        },
        {
            "name": "Nicholas Cloud",
            "url": "http://nicholascloud.com"
        },
        {
            "name": "Doug Neiner",
            "url": "http://dougneiner.com"
        },
        {
            "name": "Jonathan Creamer",
            "url": "https://github.com/jcreamer898"
        },
        {
            "name": "Elijah Manor",
            "url": "http://www.elijahmanor.com"
        },
        {
            "name": "Ger Hobbelt",
            "url": "http://hebbut.net/"
        },
        {
            "name": "Christian Haas",
            "url": "http://github.com/dertseha"
        },
        {
            "name": "Mark Swaffer",
            "url": "https://github.com/swaff"
        },
        {
            "name": "Sergio Pereira",
            "url": "https://github.com/sergiopereiraTT"
        },
        {
            "name": "Anthony van der Hoorn",
            "url": "http://blog.anthonyvanderhoorn.com/"
        },
        {
            "name": "John-David Dalton",
            "url": "http://www.allyoucanleet.com"
        },
        {
            "name": "Derick Bailey",
            "url": "http://derickbailey.com/"
        },
        {
            "name": "Kamil Biela",
            "url": "https://github.com/kamilbiela"
        },
        {
            "name": "Ryan Niemeyer",
            "url": "https://github.com/rniemeyer"
        },
        {
            "name": "Caleb Rugg",
            "url": "https://github.com/crugg"
        },
        {
            "name": "Adria Jimenez",
            "url": "https://github.com/ajimix"
        }
    ],
    "dependencies": {
        "lodash": "^4.12.0"
    },
    "description": "Pub/Sub library providing wildcard subscriptions, complex message handling, etc.  Works server and client-side.",
    "devDependencies": {
        "bower": "^1.4.1",
        "express": "^4.12.3",
        "gulp": "^3.8.8",
        "gulp-changed": "^1.2.1",
        "gulp-header": "^1.2.2",
        "gulp-imports": "~0.0.1",
        "gulp-jscs": "^1.6.0",
        "gulp-jshint": "^1.10.0",
        "gulp-plato": "^1.0.2",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.3",
        "gulp-spawn-mocha": "^2.0.1",
        "gulp-uglify": "^1.2.0",
        "gulp-util": "~2.2.9",
        "istanbul": "^0.3.13",
        "jquery": "^2.2.4",
        "jshint-stylish": "^1.0.2",
        "karma": "^0.12.31",
        "mocha": "^2.2.4",
        "open": "~0.0.4",
        "postal.diagnostics": "^0.7.4",
        "should": "^6.0.1",
        "sinon": "~1.14.1"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "7f9f035943a24daa9963ac5a53b5d0cf07df24b9",
        "tarball": "https://registry.npmjs.org/postal/-/postal-2.0.5.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "files": [
        "lib",
        "LICENSE"
    ],
    "gitHead": "c5223167b24dc18ee9442e769f56009df2ea7d43",
    "homepage": "http://github.com/postaljs/postal.js",
    "keywords": [
        "pub/sub",
        "pub",
        "sub",
        "messaging",
        "message",
        "bus",
        "event",
        "mediator",
        "broker",
        "envelope"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/mit-license.php"
        }
    ],
    "main": "lib/postal.js",
    "maintainers": [
        {
            "name": "dougneiner"
        },
        {
            "name": "ifandelse"
        },
        {
            "name": "rniemeyer"
        }
    ],
    "name": "postal",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/postaljs/postal.js.git"
    },
    "scripts": {
        "build": "gulp",
        "coverage": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -x 'spec/**/*'  -- -r spec/helpers/node-setup.js spec spec/*.spec.js",
        "show-coverage": "open ./coverage/lcov-report/index.html",
        "start": "gulp server",
        "test": "./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec",
        "test-lodash": "./node_modules/mocha/bin/mocha -r spec/helpers/node-lodash-build-setup.js spec"
    },
    "version": "2.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
