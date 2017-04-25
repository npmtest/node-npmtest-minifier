# npmtest-minifier

#### basic test coverage for  [minifier (v0.8.1)](https://github.com/fizker/minifier#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-minifier.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-minifier) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-minifier.svg)](https://travis-ci.org/npmtest/node-npmtest-minifier)

#### A simple tool for minifying CSS/JS without a big setup

[![NPM](https://nodei.co/npm/minifier.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/minifier)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-minifier/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-minifier/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-minifier/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-minifier/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-minifier/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-minifier/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-minifier/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-minifier/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-minifier/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-minifier/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-minifier/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-minifier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-minifier/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-minifier/build/test-report.html](https://npmtest.github.io/node-npmtest-minifier/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-minifier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-minifier/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-minifier/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-minifier/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-minifier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-minifier/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-minifier/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-minifier/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Benjamin Horsleben",
        "url": "http://fizkerinc.dk"
    },
    "bin": {
        "minify": "index.js"
    },
    "bugs": {
        "url": "https://github.com/fizker/minifier/issues"
    },
    "dependencies": {
        "commander": "^2.8.1",
        "css-resolve-import": "^0.1.1",
        "fmerge": "^1.2.0",
        "glob": "^7.1.1",
        "hogan.js": "^3.0.2",
        "sqwish": "~0.2.2",
        "uglify-js": "^2.4.24"
    },
    "description": "A simple tool for minifying CSS/JS without a big setup",
    "devDependencies": {
        "chai": "^3.2.0",
        "finc-chai-helpers": "~0.1.0",
        "fzkes": "^0.14.1",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "67e9333f9e25d27643bc7963e66b2dd61cf6c5b0",
        "tarball": "https://registry.npmjs.org/minifier/-/minifier-0.8.1.tgz"
    },
    "engines": {
        "node": "^4.4.7 || >=6.3.0"
    },
    "gitHead": "af4c8a8509433f10c9287c73afae2d3e43deb199",
    "homepage": "https://github.com/fizker/minifier#readme",
    "keywords": [
        "javascript js css minify minifier build"
    ],
    "license": "WTFPL",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fizker"
        }
    ],
    "name": "minifier",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/fizker/minifier.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
