# test coverage for  [archiver (v1.3.0)](https://github.com/archiverjs/node-archiver)  [![npm package](https://img.shields.io/npm/v/npmtest-archiver.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-archiver) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-archiver.svg)](https://travis-ci.org/npmtest/node-npmtest-archiver)
#### a streaming interface for archive generation

[![NPM](https://nodei.co/npm/archiver.png?downloads=true)](https://www.npmjs.com/package/archiver)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-archiver/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-archiver/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-archiver/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-archiver/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-archiver/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-archiver/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-archiver/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-archiver/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-archiver/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-archiver/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-archiver%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-archiver/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-archiver/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-archiver%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-archiver/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-archiver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-archiver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chris Talkington",
        "url": "http://christalkington.com/"
    },
    "bugs": {
        "url": "https://github.com/archiverjs/node-archiver/issues"
    },
    "dependencies": {
        "archiver-utils": "^1.3.0",
        "async": "^2.0.0",
        "buffer-crc32": "^0.2.1",
        "glob": "^7.0.0",
        "lodash": "^4.8.0",
        "readable-stream": "^2.0.0",
        "tar-stream": "^1.5.0",
        "walkdir": "^0.0.11",
        "zip-stream": "^1.1.0"
    },
    "description": "a streaming interface for archive generation",
    "devDependencies": {
        "archiver-jsdoc-theme": "^1.0.0",
        "chai": "^3.4.0",
        "jsdoc": "~3.4.0",
        "mkdirp": "^0.5.0",
        "mocha": "^3.1.1",
        "rimraf": "^2.4.2",
        "stream-bench": "^0.1.2",
        "tar": "^2.2.1",
        "yauzl": "^2.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4f2194d6d8f99df3f531e6881f14f15d55faaf22",
        "tarball": "https://registry.npmjs.org/archiver/-/archiver-1.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "14e63cdc327e7630420f15acccbfbd598e3a3c40",
    "homepage": "https://github.com/archiverjs/node-archiver",
    "keywords": [
        "archive",
        "archiver",
        "stream",
        "zip",
        "tar"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ctalkington",
            "email": "chris@christalkington.com"
        }
    ],
    "name": "archiver",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/archiverjs/node-archiver.git"
    },
    "scripts": {
        "bench": "node benchmark/simple/pack-zip.js",
        "jsdoc": "jsdoc -c jsdoc.json README.md",
        "test": "mocha --reporter dot"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
