# npmtest-copy

#### basic test coverage for  [copy (v0.3.0)](https://github.com/jonschlinkert/copy)  [![npm package](https://img.shields.io/npm/v/npmtest-copy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-copy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-copy.svg)](https://travis-ci.org/npmtest/node-npmtest-copy)

#### Copy files or directories using globs.

[![NPM](https://nodei.co/npm/copy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/copy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-copy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-copy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-copy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-copy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-copy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-copy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-copy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-copy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-copy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-copy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-copy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-copy/build/test-report.html](https://npmtest.github.io/node-npmtest-copy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-copy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-copy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-copy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-copy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-copy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-copy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-copy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-copy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bin": {
        "copy": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/copy/issues"
    },
    "dependencies": {
        "async-each": "^1.0.0",
        "bluebird": "^3.4.1",
        "extend-shallow": "^2.0.1",
        "file-contents": "^0.3.1",
        "glob-parent": "^2.0.0",
        "graceful-fs": "^4.1.4",
        "has-glob": "^0.1.1",
        "is-absolute": "^0.2.5",
        "lazy-cache": "^2.0.1",
        "log-ok": "^0.1.1",
        "matched": "^0.4.1",
        "mkdirp": "^0.5.1",
        "resolve-dir": "^0.1.0",
        "to-file": "^0.2.0"
    },
    "description": "Copy files or directories using globs.",
    "devDependencies": {
        "assert-fs": "^0.1.0",
        "assert-path": "^0.1.0",
        "delete": "^0.3.2",
        "gulp": "^3.9.1",
        "gulp-format-md": "^0.1.9",
        "gulp-unused": "^0.1.2",
        "is-buffer": "^1.1.3",
        "look-up": "^0.8.3",
        "minimist": "^1.2.0",
        "mocha": "^2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "0d5fda5e063d2dedf992b78ac060a0820caeeff3",
        "tarball": "https://registry.npmjs.org/copy/-/copy-0.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "bin",
        "index.js",
        "lib"
    ],
    "gitHead": "291a8d248f5ba970686d076165d4e7386aa0f0d7",
    "homepage": "https://github.com/jonschlinkert/copy",
    "keywords": [
        "async",
        "copy",
        "file",
        "file-system",
        "fs",
        "glob",
        "move",
        "path",
        "pattern",
        "promise",
        "stream",
        "sync",
        "system"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "doowb"
        },
        {
            "name": "jonschlinkert"
        }
    ],
    "name": "copy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/copy.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "verb": {
        "run": true,
        "toc": true,
        "layout": "default",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "related": {
            "list": [
                "expand-config",
                "expand-files",
                "expand-target",
                "expand-task",
                "export-files",
                "write"
            ]
        },
        "reflinks": [
            "gulp",
            "verb",
            "verb-readme-generator"
        ],
        "lint": {
            "reflinks": true
        }
    },
    "version": "0.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
