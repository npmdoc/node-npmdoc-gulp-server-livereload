# npmdoc-gulp-server-livereload

#### basic api documentation for  [gulp-server-livereload (v1.9.2)](https://github.com/hiddentao/gulp-server-livereload)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-server-livereload.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-server-livereload) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-server-livereload.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-server-livereload)

#### Gulp plugin to run a local webserver with livereload enabled via socket.io. Also comes with standalone command-line interface.

[![NPM](https://nodei.co/npm/gulp-server-livereload.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-server-livereload)

- [https://npmdoc.github.io/node-npmdoc-gulp-server-livereload/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-server-livereload/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-server-livereload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-server-livereload/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-server-livereload/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-server-livereload/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ramesh Nair",
        "url": "http://hiddentao.com"
    },
    "bin": {
        "livereload": "./bin/livereload.js"
    },
    "bugs": {
        "url": "https://github.com/hiddentao/gulp-server-livereload/issues"
    },
    "dependencies": {
        "commander": "^2.8.1",
        "connect": "~3.1.1",
        "connect-inject": "~0.3.2",
        "glogg": "^1.0.0",
        "gulp-util": "^3.0.7",
        "gulplog": "^1.0.0",
        "lodash": "^4.0.0",
        "node-watch": "^0.3.4",
        "node.extend": "~1.0.10",
        "open": "~0.0.5",
        "proxy-middleware": "~0.15.0",
        "serve-index": "~1.1.4",
        "serve-static": "~1.5.2",
        "socket.io": "^1.4.4",
        "through2": "~0.5.1",
        "vinyl-fs": "^1.0.0"
    },
    "description": "Gulp plugin to run a local webserver with livereload enabled via socket.io. Also comes with standalone command-line interface.",
    "devDependencies": {
        "bluebird": "^3.1.1",
        "mocha": "~1.20.1",
        "supertest": "~0.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3db227f3463cfe4f29bf65a013baa162e2a740c6",
        "tarball": "https://registry.npmjs.org/gulp-server-livereload/-/gulp-server-livereload-1.9.2.tgz"
    },
    "gitHead": "6149250d4eb266d543d9a9c944f4db315fcfc77a",
    "homepage": "https://github.com/hiddentao/gulp-server-livereload",
    "keywords": [
        "gulpplugin",
        "webserver",
        "connect",
        "livereload",
        "socket",
        "websocket"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "hiddentao"
        }
    ],
    "name": "gulp-server-livereload",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hiddentao/gulp-server-livereload.git"
    },
    "scripts": {
        "prepublish": "npm run test",
        "test": "mocha"
    },
    "version": "1.9.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
