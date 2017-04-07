# api documentation for  [webdriver-manager (v12.0.4)](https://github.com/angular/webdriver-manager#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-webdriver-manager.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-webdriver-manager) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-webdriver-manager.svg)](https://travis-ci.org/npmdoc/node-npmdoc-webdriver-manager)
#### A selenium server and browser driver manager for your end to end tests.

[![NPM](https://nodei.co/npm/webdriver-manager.png?downloads=true)](https://www.npmjs.com/package/webdriver-manager)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-webdriver-manager_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-webdriver-manager/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Craig Nishina",
        "email": "craig.nishina@gmail.com"
    },
    "bin": {
        "webdriver-manager": "bin/webdriver-manager"
    },
    "bugs": {
        "url": "https://github.com/angular/webdriver-manager/issues"
    },
    "dependencies": {
        "adm-zip": "^0.4.7",
        "chalk": "^1.1.1",
        "del": "^2.2.0",
        "glob": "^7.0.3",
        "ini": "^1.3.4",
        "minimist": "^1.2.0",
        "q": "^1.4.1",
        "request": "^2.78.0",
        "rimraf": "^2.5.2",
        "semver": "^5.3.0",
        "xml2js": "^0.4.17"
    },
    "description": "A selenium server and browser driver manager for your end to end tests.",
    "devDependencies": {
        "@types/adm-zip": "^0.4.29",
        "@types/chalk": "^0.4.28",
        "@types/form-data": "^0.0.33",
        "@types/glob": "^5.0.29",
        "@types/ini": "^1.3.28",
        "@types/jasmine": "^2.5.43",
        "@types/minimatch": "^2.0.28",
        "@types/minimist": "^1.1.28",
        "@types/node": "^7.0.4",
        "@types/q": "^0.0.32",
        "@types/request": "^0.0.39",
        "@types/rimraf": "^0.0.28",
        "@types/selenium-webdriver": "^2.53.35",
        "@types/semver": "^5.3.30",
        "@types/xml2js": "0.0.32",
        "clang-format": "^1.0.35",
        "gulp": "^3.9.1",
        "gulp-clang-format": "^1.0.23",
        "jasmine": "^2.4.1",
        "run-sequence": "^1.1.5",
        "selenium-webdriver": "~3.0.1",
        "typescript": "~2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "658e431c805bc3a7e6bf74bc819475884e6d4861",
        "tarball": "https://registry.npmjs.org/webdriver-manager/-/webdriver-manager-12.0.4.tgz"
    },
    "engines": {
        "node": ">=6.9.x"
    },
    "gitHead": "441567c5436cbd248818cadafd94451c1e91b2f0",
    "homepage": "https://github.com/angular/webdriver-manager#readme",
    "keywords": [
        "angular",
        "test",
        "testing",
        "protractor",
        "webdriver",
        "webdriverjs",
        "selenium",
        "selenium-webdriver"
    ],
    "license": "MIT",
    "main": "built/lib/webdriver.js",
    "maintainers": [
        {
            "name": "angularcore",
            "email": "angular-core+npm@google.com"
        }
    ],
    "name": "webdriver-manager",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/angular/webdriver-manager.git"
    },
    "scripts": {
        "check_format": "gulp format:enforce",
        "format": "gulp format",
        "prepublish": "gulp prepublish",
        "test": "gulp test",
        "test_circle_e2e": "gulp test:e2e:no_kvm",
        "test_unit": "gulp test:unit"
    },
    "version": "12.0.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module webdriver-manager](#apidoc.module.webdriver-manager)



# <a name="apidoc.module.webdriver-manager"></a>[module webdriver-manager](#apidoc.module.webdriver-manager)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
