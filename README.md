# npmdoc-electron-prebuilt

#### basic api documentation for  [electron-prebuilt (v1.4.13)](https://github.com/electron-userland/electron-prebuilt#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-prebuilt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-prebuilt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-prebuilt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-prebuilt)

#### Install prebuilt electron binaries for the command-line using npm

[![NPM](https://nodei.co/npm/electron-prebuilt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-prebuilt)

- [https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus"
    },
    "bin": {
        "electron": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/electron-userland/electron-prebuilt/issues"
    },
    "dependencies": {
        "electron-download": "^3.0.1",
        "extract-zip": "^1.0.3"
    },
    "deprecated": "electron-prebuilt has been renamed to electron. For more details, see http://electron.atom.io/blog/2016/08/16/npm-install-electron",
    "description": "Install prebuilt electron binaries for the command-line using npm",
    "devDependencies": {
        "home-path": "^0.1.1",
        "path-exists": "^2.0.0",
        "standard": "^5.4.1",
        "tape": "^3.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "0a0e4d7bf895a242061ccfab29394dcda1da33d2",
        "tarball": "https://registry.npmjs.org/electron-prebuilt/-/electron-prebuilt-1.4.13.tgz"
    },
    "homepage": "https://github.com/electron-userland/electron-prebuilt#readme",
    "keywords": [
        "electron"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "electron"
        }
    ],
    "name": "electron-prebuilt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/electron-userland/electron-prebuilt.git"
    },
    "scripts": {
        "cache-clean": "rm -rf ~/.electron && rm -rf dist",
        "postinstall": "node install.js",
        "pretest": "npm run cache-clean && npm run postinstall",
        "test": "tape test/*.js && standard"
    },
    "version": "1.4.13"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
