# npmtest-grunt-phantomas

#### basic test coverage for  [grunt-phantomas (v0.14.0)](https://github.com/stefanjudis/grunt-phantomas)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-phantomas.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-phantomas) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-phantomas.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-phantomas)

#### Grunt plugin for phantomas

[![NPM](https://nodei.co/npm/grunt-phantomas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-phantomas)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-phantomas/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-phantomas/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-phantomas/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-phantomas/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-phantomas/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-phantomas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-phantomas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-phantomas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-phantomas/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-phantomas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "stefan judis",
        "url": "http://stefanjudis.de"
    },
    "bugs": {
        "url": "https://github.com/stefanjudis/grunt-phantomas/issues"
    },
    "dependencies": {
        "bluebird": "~3.4.7",
        "html-minifier": "~3.2.3",
        "json2csv": "~3.7.3",
        "lodash": "~4.17.4",
        "node-fs": "~0.1.7",
        "phantomas": "~1.18.0"
    },
    "description": "Grunt plugin for phantomas",
    "devDependencies": {
        "coveralls": "~2.11.0",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-compass": "~1.1.1",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-contrib-jshint": "~1.1.0",
        "grunt-contrib-nodeunit": "~1.0.0",
        "grunt-contrib-uglify": "~2.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-jscs": "^3.0.1",
        "jscoverage": "~0.6.0",
        "nodeunit": "~0.10.2"
    },
    "directories": {},
    "dist": {
        "shasum": "d579f398b0c2e6e816ddebda6fc120bd44733f5f",
        "tarball": "https://registry.npmjs.org/grunt-phantomas/-/grunt-phantomas-0.14.0.tgz"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "e50a05e73ce7c8b6dcb7a084819794833c3b4871",
    "homepage": "https://github.com/stefanjudis/grunt-phantomas",
    "keywords": [
        "gruntplugin",
        "phantomas",
        "performance",
        "metrics",
        "phantomjs"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/stefanjudis/grunt-phantomas/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "stefanjudis"
        }
    ],
    "name": "grunt-phantomas",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stefanjudis/grunt-phantomas.git"
    },
    "scripts": {
        "coveralls": "jscoverage tasks/lib/phantomas.js && PHANTOMAS_COV=1 nodeunit --reporter=lcov test/lib/phantomasTest.js | coveralls",
        "grunt": "grunt",
        "test": "grunt test"
    },
    "version": "0.14.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
