# npmdoc-browser-run

#### api documentation for  [browser-run (v4.0.2)](https://github.com/juliangruber/browser-run)  [![npm package](https://img.shields.io/npm/v/npmdoc-browser-run.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-browser-run) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-browser-run.svg)](https://travis-ci.org/npmdoc/node-npmdoc-browser-run)

#### Transform stream that executes JavaScript it receives in a real browser and outputs console output

[![NPM](https://nodei.co/npm/browser-run.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browser-run)

- [https://npmdoc.github.io/node-npmdoc-browser-run/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browser-run/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browser-run/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browser-run/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-browser-run/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-browser-run/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julian Gruber",
        "url": "http://juliangruber.com"
    },
    "bin": {
        "browser-run": "./bin/bin.js"
    },
    "bugs": {
        "url": "https://github.com/juliangruber/browser-run/issues"
    },
    "dependencies": {
        "browser-launcher": "^1.0.0",
        "duplexer": "^0.1.1",
        "ecstatic": "^2.0.0",
        "electron-stream": "^5.0.0",
        "enstore": "^1.0.1",
        "html-inject-script": "^1.1.0",
        "optimist": "^0.6.1",
        "phantomjs-stream": "^1.1.1",
        "server-destroy": "^1.0.1",
        "source-map-support": "^0.4.0",
        "through": "^2.3.8",
        "xhr-write-stream": "^0.1.2",
        "xtend": "^4.0.1"
    },
    "description": "Transform stream that executes JavaScript it receives in a real browser and outputs console output",
    "devDependencies": {
        "browserify": "^14.1.0",
        "concat-stream": "^1.5.1",
        "phantomjs-prebuilt-that-works": "^3.0.1",
        "tap": "^10.0.1",
        "tree-kill": "^1.0.0",
        "utf8-stream": "^0.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b2ed799f1102656f9a456cff2be7893f819c6bc6",
        "tarball": "https://registry.npmjs.org/browser-run/-/browser-run-4.0.2.tgz"
    },
    "gitHead": "cb39268cedcb9fcd30a90a6bb9a4686032b08410",
    "homepage": "https://github.com/juliangruber/browser-run",
    "keywords": [
        "browser",
        "stream",
        "phantomjs",
        "test",
        "headless",
        "duplex"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "juliangruber"
        }
    ],
    "name": "browser-run",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/juliangruber/browser-run.git"
    },
    "scripts": {
        "prepublish": "make build",
        "test": "make test"
    },
    "version": "4.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
