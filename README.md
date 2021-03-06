# npmdoc-pngjs

#### api documentation for  [pngjs (v3.0.1)](https://github.com/lukeapage/pngjs)  [![npm package](https://img.shields.io/npm/v/npmdoc-pngjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pngjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pngjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pngjs)

#### PNG encoder/decoder in pure JS, supporting any bit size & interlace, async & sync with full test suite.

[![NPM](https://nodei.co/npm/pngjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pngjs)

- [https://npmdoc.github.io/node-npmdoc-pngjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pngjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pngjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pngjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pngjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pngjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pngjs",
    "version": "3.0.1",
    "description": "PNG encoder/decoder in pure JS, supporting any bit size & interlace, async & sync with full test suite.",
    "contributors": [
        "Alexandre Paré",
        "Gaurav Mali",
        "Gusts Kaksis",
        "Kuba Niegowski",
        "Luke Page",
        "Pietajan De Potter",
        "Steven Sojka",
        "liangzeng",
        "Michael Vogt",
        "Xin-Xin Wang"
    ],
    "homepage": "https://github.com/lukeapage/pngjs",
    "keywords": [
        "PNG",
        "decoder",
        "encoder",
        "js-png",
        "node-png",
        "parser",
        "png",
        "png-js",
        "png-parse",
        "pngjs"
    ],
    "engines": {
        "node": ">=4.0.0"
    },
    "main": "./lib/png.js",
    "directories": {
        "example": "examples"
    },
    "scripts": {
        "coverage": "istanbul -- cover node_modules/tape/bin/tape test/*-spec.js nolarge",
        "coverage-report": "npm run coverage && istanbul report html",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "test": "npm run lint && tape test/*-spec.js | tap-dot && node test/run-compare",
        "lint": "eslint lib"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/lukeapage/pngjs2.git"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/lukeapage/pngjs2/issues"
    },
    "devDependencies": {
        "buffer-equal": "1.0.0",
        "connect": "^3.4.0",
        "eslint": "^3.2.2",
        "istanbul": "^0.4.4",
        "phantomjs-prebuilt": "^2.1.7",
        "serve-static": "^1.10.0",
        "tap-dot": "^1.0.0",
        "tape": "^4.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
