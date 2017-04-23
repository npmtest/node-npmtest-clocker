# npmtest-clocker

#### basic test coverage for  [clocker (v1.11.3)](https://github.com/substack/clocker)  [![npm package](https://img.shields.io/npm/v/npmtest-clocker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clocker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clocker.svg)](https://travis-ci.org/npmtest/node-npmtest-clocker)

#### track project hours

[![NPM](https://nodei.co/npm/clocker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clocker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clocker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clocker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clocker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clocker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clocker/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-clocker/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-clocker/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clocker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clocker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-clocker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-clocker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clocker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-clocker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-clocker/build/test-report.html](https://npmtest.github.io/node-npmtest-clocker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-clocker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clocker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-clocker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clocker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clocker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clocker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clocker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clocker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "clocker",
    "version": "1.11.3",
    "description": "track project hours",
    "bin": {
        "clocker": "bin/cmd.js"
    },
    "dependencies": {
        "editor": "^0.1.0",
        "json-stable-stringify": "^1.0.0",
        "level": "^1.3.0",
        "minimist": "0.0.10",
        "mkdirp": "^0.3.5",
        "parse-messy-time": "^1.2.1",
        "strftime": "~0.6.2",
        "through": "^2.3.7"
    },
    "devDependencies": {
        "tape": "~2.3.2"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/clocker.git"
    },
    "homepage": "https://github.com/substack/clocker",
    "keywords": [
        "consulting",
        "hours",
        "time",
        "tracking",
        "invoice"
    ],
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
