# npmtest-barbeque

#### test coverage for  [barbeque (v0.2.4)](https://github.com/pilwon/barbeque)  [![npm package](https://img.shields.io/npm/v/npmtest-barbeque.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-barbeque) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-barbeque.svg)](https://travis-ci.org/npmtest/node-npmtest-barbeque)

#### Redis-based task queue library for Node.js, inspired by Celery and Kue.

[![NPM](https://nodei.co/npm/barbeque.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/barbeque)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-barbeque/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-barbeque/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-barbeque/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-barbeque/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-barbeque/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-barbeque/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-barbeque/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-barbeque/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-barbeque/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-barbeque/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-barbeque/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-barbeque/build/test-report.html](https://npmtest.github.io/node-npmtest-barbeque/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-barbeque/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-barbeque/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-barbeque/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-barbeque/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-barbeque/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-barbeque/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-barbeque/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-barbeque/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pilwon Huh"
    },
    "bin": {
        "barbeque": "./bin/bbq",
        "bbq": "./bin/bbq"
    },
    "bugs": {
        "url": "https://github.com/pilwon/barbeque/issues"
    },
    "dependencies": {
        "async": "0.2.9",
        "browserify-middleware": "1.19.0",
        "colors": "0.6.2",
        "express": "3.4.4",
        "hbs": "2.4.0",
        "less-middleware": "0.1.14",
        "lodash": "2.2.1",
        "moment": "2.4.0",
        "redis": "0.9.0",
        "socket.io": "0.9.16",
        "uuid": "1.4.1"
    },
    "description": "Redis-based task queue library for Node.js, inspired by Celery and Kue.",
    "devDependencies": {
        "grunt": "0.4.1",
        "grunt-contrib-jshint": "0.7.1",
        "grunt-contrib-watch": "0.4.3",
        "matchdep": "0.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3aaefd3c1b24ec7d8a3ceddca7a92034a5ef3ad9",
        "tarball": "https://registry.npmjs.org/barbeque/-/barbeque-0.2.4.tgz"
    },
    "homepage": "https://github.com/pilwon/barbeque",
    "keywords": [
        "barbeque",
        "barbecue",
        "bbq",
        "task",
        "job",
        "queue",
        "kue",
        "schedule",
        "delay",
        "worker",
        "redis",
        "db",
        "pubsub"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "pilwon"
        }
    ],
    "name": "barbeque",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/pilwon/barbeque.git"
    },
    "scripts": {
        "prepublish": "npm prune"
    },
    "version": "0.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
