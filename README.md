# npmtest-browser-cookies

#### basic test coverage for  browser-cookies (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-browser-cookies.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-browser-cookies) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-browser-cookies.svg)](https://travis-ci.org/npmtest/node-npmtest-browser-cookies)

#### Tiny cookies library for the browser

[![NPM](https://nodei.co/npm/browser-cookies.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browser-cookies)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-browser-cookies/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-cookies/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-browser-cookies/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-browser-cookies/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-browser-cookies/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-browser-cookies/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-browser-cookies/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-browser-cookies/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-browser-cookies/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-cookies/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-browser-cookies/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-browser-cookies/build/test-report.html](https://npmtest.github.io/node-npmtest-browser-cookies/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-browser-cookies/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-browser-cookies/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-browser-cookies/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browser-cookies/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browser-cookies/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browser-cookies/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-browser-cookies/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-browser-cookies/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "browser-cookies",
    "description": "Tiny cookies library for the browser",
    "version": "1.1.0",
    "main": "src/browser-cookies.js",
    "files": [
        "src/browser-cookies.js",
        "README.md",
        "LICENCE"
    ],
    "dependencies": {},
    "devDependencies": {
        "browserify": "13.1.1",
        "concurrently": "3.1.0",
        "coveralls": "2.11.15",
        "gulp": "git://github.com/gulpjs/gulp.git#4.0",
        "gulp-rename": "1.2.2",
        "gulp-size": "2.1.0",
        "gulp-uglify": "2.0.0",
        "gulp-wrap": "0.13.0",
        "karma": "1.3.0",
        "karma-coverage": "1.1.1",
        "karma-jasmine": "0.1.6",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-spec-reporter": "0.0.26",
        "phantomjs-prebuilt": "2.1.14",
        "watchify": "3.8.0",
        "zuul": "3.11.1",
        "zuul-ngrok": "4.0.0"
    },
    "scripts": {
        "build": "node ./node_modules/gulp/bin/gulp.js build",
        "test:local": "node ./node_modules/gulp/bin/gulp.js localtest",
        "test:full": "concurrently \"node ./node_modules/gulp/bin/gulp.js build\" \"node ./node_modules/zuul/bin/zuul -- test/*.js\"",
        "test": "concurrently \"node ./node_modules/gulp/bin/gulp.js coverage\" \"node ./node_modules/zuul/bin/zuul -- test/*.js\""
    },
    "author": {
        "name": "Voltace",
        "url": "http://www.voltace.com/"
    },
    "license": "Unlicence",
    "repository": {
        "type": "git",
        "url": "git://github.com/voltace/browser-cookies"
    },
    "bugs": {
        "url": "https://github.com/voltace/browser-cookies/issues"
    },
    "keywords": [
        "cookies",
        "cookie",
        "client"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
