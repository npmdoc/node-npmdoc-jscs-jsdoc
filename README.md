# npmdoc-jscs-jsdoc

#### api documentation for  [jscs-jsdoc (v2.0.0)](https://github.com/jscs-dev/jscs-jsdoc)  [![npm package](https://img.shields.io/npm/v/npmdoc-jscs-jsdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jscs-jsdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jscs-jsdoc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jscs-jsdoc)

#### JSCS jsdoc plugin

[![NPM](https://nodei.co/npm/jscs-jsdoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jscs-jsdoc)

- [https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jscs-jsdoc",
    "author": "Alexej Yaroshevich <alex@qfox.ru>",
    "description": "JSCS jsdoc plugin",
    "version": "2.0.0",
    "main": "lib/index",
    "homepage": "https://github.com/jscs-dev/jscs-jsdoc",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/jscs-dev/jscs-jsdoc"
    },
    "bugs": {
        "url": "https://github.com/jscs-dev/jscs-jsdoc/issues"
    },
    "contributors": [
        "Alexej Yaroshevich <alex@qfox.ru>",
        "Henry Zhu <hi@henryzoo.com>",
        "Christopher Hiller <chiller@badwing.com>",
        "Raphael Pigulla <raphael.pigulla@tngtech.com>"
    ],
    "engines": {
        "node": ">= 0.8.0"
    },
    "dependencies": {
        "comment-parser": "^0.3.1",
        "jsdoctypeparser": "~1.2.0"
    },
    "devDependencies": {
        "chai": "^2.3.0",
        "chai-subset": "^1.1.0",
        "jscs": "git://github.com/jscs-dev/node-jscs.git#master",
        "jshint": "^2.7.0",
        "mocha": "^2.2.4"
    },
    "scripts": {
        "lint": "jshint lib test && jscs lib test",
        "test": "npm run lint && mocha",
        "browserify": "browserify --standalone JsdocJscsPlugin lib/index.js -o jscs-jsdoc-browser.js",
        "changelog": "changelog-maker jscs-dev jscs-jsdoc --group"
    },
    "files": [
        "lib",
        "LICENSE"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/jscs-dev/jscs-jsdoc/raw/master/LICENSE"
        }
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
