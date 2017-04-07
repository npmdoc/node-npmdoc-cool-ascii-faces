# api documentation for  [cool-ascii-faces (v1.3.4)](https://github.com/maxogden/cool-ascii-faces)  [![npm package](https://img.shields.io/npm/v/npmdoc-cool-ascii-faces.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cool-ascii-faces) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cool-ascii-faces.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cool-ascii-faces)
#### get some cool ascii faces ヽ༼ຈل͜ຈ༽ﾉ

[![NPM](https://nodei.co/npm/cool-ascii-faces.png?downloads=true)](https://www.npmjs.com/package/cool-ascii-faces)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cool-ascii-faces/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-cool-ascii-faces%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cool-ascii-faces/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cool-ascii-faces/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cool-ascii-faces/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "cool-face": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/cool-ascii-faces/issues"
    },
    "dependencies": {
        "stream-spigot": "~3.0.3"
    },
    "description": "get some cool ascii faces ヽ༼ຈل͜ຈ༽ﾉ",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "f16a3a77dd59441481276ca4673e6a47c66fb0b2",
        "tarball": "https://registry.npmjs.org/cool-ascii-faces/-/cool-ascii-faces-1.3.4.tgz"
    },
    "gitHead": "c7c04b4c7ce2877bf663efdfac4dcc182b53fe4e",
    "homepage": "https://github.com/maxogden/cool-ascii-faces",
    "license": "BSD",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bret",
            "email": "bcomnes@gmail.com"
        },
        {
            "name": "maxogden",
            "email": "max@maxogden.com"
        }
    ],
    "name": "cool-ascii-faces",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/maxogden/cool-ascii-faces.git"
    },
    "scripts": {
        "test": "node test.js"
    },
    "version": "1.3.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cool-ascii-faces](#apidoc.module.cool-ascii-faces)
1.  [function <span class="apidocSignatureSpan">cool-ascii-faces.</span>faceStream ()](#apidoc.element.cool-ascii-faces.faceStream)
1.  object <span class="apidocSignatureSpan">cool-ascii-faces.</span>faces



# <a name="apidoc.module.cool-ascii-faces"></a>[module cool-ascii-faces](#apidoc.module.cool-ascii-faces)

#### <a name="apidoc.element.cool-ascii-faces.faceStream"></a>[function <span class="apidocSignatureSpan">cool-ascii-faces.</span>faceStream ()](#apidoc.element.cool-ascii-faces.faceStream)
- description and source-code
```javascript
faceStream = function () {
  return spigot(faces)
}
```
- example usage
```shell
...
  "=͟͟͞͞ =͟͟͞͞ ﾍ( ´Д')ﾉ",
  "(((╹д╹;)))",
  "•̀.̫•́✧",
  "(ᵒ̤̑ ₀̑ ᵒ̤̑)",
  "\_(ʘ_ʘ)_/"
]

cool.faceStream()
// create a readable stream of all the faces
'''
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
