# api documentation for  [electron-prebuilt (v1.4.13)](https://github.com/electron-userland/electron-prebuilt#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-prebuilt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-prebuilt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-prebuilt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-prebuilt)
#### Install prebuilt electron binaries for the command-line using npm

[![NPM](https://nodei.co/npm/electron-prebuilt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-prebuilt)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-prebuilt/build/apidoc.html)

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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module electron-prebuilt](#apidoc.module.electron-prebuilt)
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>0
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>1
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>10
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>11
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>12
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>13
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>14
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>15
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>16
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>17
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>18
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>19
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>2
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>20
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>21
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>22
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>23
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>24
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>25
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>26
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>27
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>28
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>29
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>3
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>30
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>31
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>32
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>33
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>34
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>35
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>36
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>37
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>38
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>39
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>4
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>40
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>41
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>42
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>43
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>44
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>45
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>46
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>47
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>48
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>49
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>5
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>50
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>51
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>52
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>53
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>54
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>55
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>56
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>57
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>58
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>59
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>6
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>60
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>61
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>62
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>63
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>64
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>65
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>66
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>67
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>68
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>69
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>7
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>70
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>71
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>72
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>73
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>74
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>75
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>76
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>77
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>78
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>79
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>8
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>80
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>81
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>82
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>83
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>84
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>85
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>86
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>87
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>88
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>89
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>9
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>90
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>91
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>92
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>93
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>94
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>95
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>96
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>97
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>98
1.  string <span class="apidocSignatureSpan">electron-prebuilt.</span>99



# <a name="apidoc.module.electron-prebuilt"></a>[module electron-prebuilt](#apidoc.module.electron-prebuilt)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
