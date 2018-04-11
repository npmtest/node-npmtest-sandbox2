# npmtest-sandbox2

#### basic test coverage for  [sandbox2 (v2018.4.11)](https://github.com/kaizhu256/node-sandbox2)  [![npm package](https://img.shields.io/npm/v/npmtest-sandbox2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sandbox2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sandbox2.svg)](https://travis-ci.org/npmtest/node-npmtest-sandbox2)

#### this is a test app

[![NPM](https://nodei.co/npm/sandbox2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sandbox2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sandbox2/tree/alpha)|
|--:|:--|
| coverage : | [![coverage](https://npmtest.github.io/node-npmtest-sandbox2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sandbox2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sandbox2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sandbox2/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sandbox2/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sandbox2/build/app) || build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sandbox2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sandbox2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sandbox2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sandbox2/build/coverage.html/index.html)

[![coverage](https://npmtest.github.io/node-npmtest-sandbox2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sandbox2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sandbox2/build/test-report.html](https://npmtest.github.io/node-npmtest-sandbox2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sandbox2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sandbox2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sandbox2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sandbox2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sandbox2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sandbox2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sandbox2/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sandbox2/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "kai zhu"
    },
    "bugs": {
        "url": "https://github.com/kaizhu256/node-sandbox2/issues"
    },
    "dependencies": {},
    "description": "this is a test app",
    "devDependencies": {
        "electron-lite": "github:kaizhu256/node-electron-lite#alpha",
        "utility2": "github:kaizhu256/node-utility2#alpha"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-ZvqDuh/fkORzeDEacXMOjjaSq8kqFgzHh69JtIjiRJpAMgBruenZgA3qjxb0dWn4Oph14uznQoH/BBHGslj/Pw==",
        "shasum": "d56b0eb0ce93057d13ff20f78768329e9c36ebae",
        "tarball": "https://registry.npmjs.org/sandbox2/-/sandbox2-2018.4.11.tgz",
        "fileCount": 5,
        "unpackedSize": 36810
    },
    "engines": {
        "node": ">=4.0"
    },
    "homepage": "https://github.com/kaizhu256/node-sandbox2",
    "keywords": [],
    "license": "MIT",
    "main": "lib.sandbox2.js",
    "maintainers": [
        {
            "name": "kaizhu"
        }
    ],
    "name": "sandbox2",
    "nameAliasPublish": "",
    "nameLib": "sandbox2",
    "nameOriginal": "sandbox2",
    "optionalDependencies": {},
    "os": [
        "darwin",
        "linux"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kaizhu256/node-sandbox2.git"
    },
    "scripts": {
        "apidocRawCreate": "[ ! -f npm_scripts.sh ] || ./npm_scripts.sh shNpmScriptApidocRawCreate",
        "apidocRawFetch": "[ ! -f npm_scripts.sh ] || ./npm_scripts.sh shNpmScriptApidocRawFetch",
        "build-ci": "utility2 shReadmeTest build_ci.sh",
        "env": "env",
        "heroku-postbuild": "npm uninstall utility2 2>/dev/null; npm install kaizhu256/node-utility2#alpha && utility2 shDeployHeroku",
        "postinstall": "[ ! -f npm_scripts.sh ] || ./npm_scripts.sh shNpmScriptPostinstall",
        "start": "PORT=${PORT:-8080} utility2 start test.js",
        "test": "PORT=$(utility2 shServerPortRandom) utility2 test test.js"
    },
    "version": "2018.4.11",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
