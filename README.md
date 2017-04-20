# npmtest-loopback-angular-admin

#### basic test coverage for  [loopback-angular-admin (v0.0.7)](https://github.com/beeman/loopback-angular-admin)  [![npm package](https://img.shields.io/npm/v/npmtest-loopback-angular-admin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-loopback-angular-admin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-loopback-angular-admin.svg)](https://travis-ci.org/npmtest/node-npmtest-loopback-angular-admin)

#### Quickly create admin interfaces on a Loopback 2.x API

[![NPM](https://nodei.co/npm/loopback-angular-admin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/loopback-angular-admin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-loopback-angular-admin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-loopback-angular-admin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-loopback-angular-admin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/test-report.html](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-loopback-angular-admin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-loopback-angular-admin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-loopback-angular-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-loopback-angular-admin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-loopback-angular-admin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "loopback-angular-admin",
    "description": "Quickly create admin interfaces on a Loopback 2.x API",
    "version": "0.0.7",
    "engines": {
        "node": "0.10.x"
    },
    "homepage": "https://github.com/beeman/loopback-angular-admin",
    "author": "Bram Borggreve <borggreve@gmail.com>",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/beeman/loopback-angular-admin"
    },
    "bugs": {
        "url": "https://github.com/beeman/loopback-angular-admin/issues"
    },
    "scripts": {
        "pretest": "jshint .",
        "start": "node server/server.js",
        "dev": "nodemon server/server.js --watch server common",
        "postinstall": "grunt build"
    },
    "main": "server/server.js",
    "dependencies": {
        "bower": "^1.3.12",
        "compression": "^1.1.1",
        "errorhandler": "^1.2.1",
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "load-grunt-tasks": "^0.6.0",
        "loopback": "^2.5.0",
        "loopback-boot": "^2.1.0",
        "loopback-component-storage": "^1.0.5",
        "loopback-connector-mongodb": "^1.4.4",
        "serve-favicon": "^2.1.5",
        "showdown": "^0.3.1"
    },
    "optionalDependencies": {
        "loopback-explorer": "^1.3.0"
    },
    "devDependencies": {
        "grunt-autoprefixer": "^1.0.1",
        "grunt-concurrent": "^1.0.0",
        "grunt-connect-proxy": "^0.1.11",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-concat": "^0.5.0",
        "grunt-contrib-connect": "^0.8.0",
        "grunt-contrib-copy": "^0.7.0",
        "grunt-contrib-cssmin": "^0.10.0",
        "grunt-contrib-htmlmin": "^0.3.0",
        "grunt-contrib-imagemin": "^0.8.1",
        "grunt-contrib-jshint": "^0.10.0",
        "grunt-contrib-uglify": "^0.6.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-docular": "^0.2.2",
        "grunt-filerev": "^2.1.0",
        "grunt-google-cdn": "^0.4.3",
        "grunt-karma": "^0.9.0",
        "grunt-loopback-angular": "^1.1.0",
        "grunt-newer": "^0.7.0",
        "grunt-ng-constant": "^1.0.0",
        "grunt-ngmin": "^0.0.3",
        "grunt-svgmin": "^1.0.0",
        "grunt-usemin": "^2.4.0",
        "grunt-wiredep": "^1.9.0",
        "jshint": "^2.5.6",
        "jshint-stylish": "^1.0.0",
        "karma": "^0.12.24",
        "karma-jasmine": "^0.1.5",
        "karma-phantomjs-launcher": "^0.1.4",
        "time-grunt": "^1.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
