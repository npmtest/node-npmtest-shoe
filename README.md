# npmtest-shoe

#### test coverage for  [shoe (v0.0.15)](https://github.com/substack/shoe)  [![npm package](https://img.shields.io/npm/v/npmtest-shoe.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shoe) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shoe.svg)](https://travis-ci.org/npmtest/node-npmtest-shoe)

#### streaming sockjs for node and the browser

[![NPM](https://nodei.co/npm/shoe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shoe)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shoe/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shoe/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shoe/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shoe/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shoe/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shoe/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shoe/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shoe/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shoe/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shoe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shoe/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shoe/build/test-report.html](https://npmtest.github.io/node-npmtest-shoe/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shoe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shoe/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shoe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shoe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shoe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shoe/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shoe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shoe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "browserify": "browser.js",
    "bugs": {
        "url": "https://github.com/substack/shoe/issues"
    },
    "bundleDependencies": [
        "sockjs-client"
    ],
    "dependencies": {
        "sockjs": "0.3.7",
        "sockjs-client": "*"
    },
    "description": "streaming sockjs for node and the browser",
    "devDependencies": {
        "tape": "~1.0.4",
        "testling": "~1.4.1",
        "through": "~2.3.4"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "baed8f1a7f08f530b66f0914287fcaa65b12443a",
        "tarball": "https://registry.npmjs.org/shoe/-/shoe-0.0.15.tgz"
    },
    "engine": {
        "node": ">=0.6"
    },
    "homepage": "https://github.com/substack/shoe",
    "keywords": [
        "websocket",
        "stream",
        "sock",
        "browserify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        }
    ],
    "name": "shoe",
    "optionalDependencies": {},
    "readmeFilename": "readme.markdown",
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/shoe.git"
    },
    "scripts": {
        "test": "testling ."
    },
    "testling": {
        "files": "test/browser.js",
        "server": "test/server.js",
        "browsers": [
            "ie/8..latest",
            "chrome/latest",
            "firefox/latest",
            "safari/latest",
            "opera/latest",
            "iphone/latest",
            "ipad/latest",
            "android/latest"
        ]
    },
    "version": "0.0.15"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
