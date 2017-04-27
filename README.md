# npmtest-peerflix-server

#### basic test coverage for  [peerflix-server (v0.1.3)](https://github.com/asapach/peerflix-server#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-peerflix-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-peerflix-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-peerflix-server.svg)](https://travis-ci.org/npmtest/node-npmtest-peerflix-server)

#### Streaming torrent client for node.js with web ui.

[![NPM](https://nodei.co/npm/peerflix-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/peerflix-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-peerflix-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-peerflix-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-peerflix-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-peerflix-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-peerflix-server/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-peerflix-server/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-peerflix-server/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-peerflix-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-peerflix-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-peerflix-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-peerflix-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-peerflix-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-peerflix-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-peerflix-server/build/test-report.html](https://npmtest.github.io/node-npmtest-peerflix-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-peerflix-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-peerflix-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-peerflix-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-peerflix-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-peerflix-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-peerflix-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-peerflix-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-peerflix-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aliaksei Sapach"
    },
    "bin": {
        "peerflix-server": "./server/bin.js"
    },
    "bugs": {
        "url": "https://github.com/asapach/peerflix-server/issues"
    },
    "dependencies": {
        "connect-multiparty": "^1.2.5",
        "express": "~3.5.1",
        "fluent-ffmpeg": "^2.0.0-rc3",
        "lodash": "~2.4.1",
        "mkdirp": "^0.5.0",
        "pump": "^1.0.0",
        "range-parser": "^1.0.2",
        "read-torrent": "^1.3.0",
        "socket.io": "^1.5.1",
        "torrent-stream": "^0.18.1"
    },
    "description": "Streaming torrent client for node.js with web ui.",
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-autoprefixer": "~0.7.3",
        "grunt-concurrent": "~0.5.0",
        "grunt-contrib-clean": "~0.5.0",
        "grunt-contrib-concat": "~0.4.0",
        "grunt-contrib-connect": "^0.10.1",
        "grunt-contrib-copy": "~0.5.0",
        "grunt-contrib-cssmin": "~0.9.0",
        "grunt-contrib-htmlmin": "~0.3.0",
        "grunt-contrib-jshint": "~0.10.0",
        "grunt-contrib-uglify": "~0.4.0",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-karma": "^2.0.0",
        "grunt-newer": "~0.7.0",
        "grunt-ngmin": "~0.0.3",
        "grunt-rev": "~0.1.0",
        "grunt-svgmin": "~0.4.0",
        "grunt-usemin": "~2.1.1",
        "grunt-wiredep": "~1.7.0",
        "jshint-stylish": "~0.2.0",
        "karma": "^0.13.22",
        "karma-jasmine": "~0.1.5",
        "karma-ng-html2js-preprocessor": "~0.1.0",
        "karma-phantomjs-launcher": "~0.1.4",
        "load-grunt-tasks": "~0.4.0",
        "time-grunt": "~0.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1f3c2b81188de82482f64cf89d015f5428e4c4e5",
        "tarball": "https://registry.npmjs.org/peerflix-server/-/peerflix-server-0.1.3.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "3aad03e8b1e2379ff9820c5ac14b5f9ea295b75d",
    "homepage": "https://github.com/asapach/peerflix-server#readme",
    "keywords": [
        "bittorrent",
        "torrent",
        "stream",
        "peerflix",
        "server",
        "web"
    ],
    "license": "MIT",
    "main": "./server/bin.js",
    "maintainers": [
        {
            "name": "asapach"
        }
    ],
    "name": "peerflix-server",
    "optionalDependencies": {
        "fluent-ffmpeg": "^2.0.0-rc3"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/asapach/peerflix-server.git"
    },
    "scripts": {
        "start": "node ./server/bin.js",
        "test": "grunt test"
    },
    "version": "0.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
