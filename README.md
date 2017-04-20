# npmdoc-node-curl

#### api documentation for  [node-curl (v0.3.3)](http://github.com/jiangmiao/node-curl)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-curl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-curl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-curl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-curl)

#### node wrapper for multi curl, fully implemented.

[![NPM](https://nodei.co/npm/node-curl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-curl)

- [https://npmdoc.github.io/node-npmdoc-node-curl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-curl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-curl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-curl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-curl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-curl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-curl",
    "version": "0.3.3",
    "author": "Jiang Miao <jiangfriend@gmail.com>",
    "description": "node wrapper for multi curl, fully implemented.",
    "keywords": [
        "node-curl",
        "curl",
        "multi-curl",
        "mcurl"
    ],
    "homepage": "http://github.com/jiangmiao/node-curl",
    "repository": {
        "type": "git",
        "url": "git://github.com/jiangmiao/node-curl.git"
    },
    "main": "./lib",
    "scripts": {
        "install": "sh src/generate_curl_options_list.sh && (node-gyp rebuild || node-waf configure build)"
    },
    "engines": {
        "node": ">= 0.6.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
