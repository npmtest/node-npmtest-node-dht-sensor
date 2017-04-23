# npmtest-node-dht-sensor

#### basic test coverage for  node-dht-sensor (v0.0.32)  [![npm package](https://img.shields.io/npm/v/npmtest-node-dht-sensor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-dht-sensor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-dht-sensor.svg)](https://travis-ci.org/npmtest/node-npmtest-node-dht-sensor)

#### Reads data from DHT sensors on Raspberry Pi

[![NPM](https://nodei.co/npm/node-dht-sensor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-dht-sensor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-dht-sensor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-dht-sensor/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-dht-sensor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-dht-sensor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-dht-sensor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-dht-sensor/build/test-report.html](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-dht-sensor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-dht-sensor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "David Momenso",
    "name": "node-dht-sensor",
    "description": "Reads data from DHT sensors on Raspberry Pi",
    "version": "0.0.32",
    "repository": {
        "url": "https://github.com/momenso/node-dht-sensor"
    },
    "scripts": {
        "preinstall": "./check-lib.sh",
        "install": "node-gyp configure",
        "postinstall": "node-gyp build"
    },
    "main": "./build/Release/node_dht_sensor",
    "dependencies": {
        "nan": "^2.4.0"
    },
    "license": "LGPL-3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
