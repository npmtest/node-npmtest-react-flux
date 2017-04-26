# npmtest-react-flux

#### basic test coverage for  [react-flux (v1.0.1)](https://github.com/kjda/ReactFlux)  [![npm package](https://img.shields.io/npm/v/npmtest-react-flux.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-flux) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-flux.svg)](https://travis-ci.org/npmtest/node-npmtest-react-flux)

#### A library implementing React Flux data flow

[![NPM](https://nodei.co/npm/react-flux.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-flux)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-flux/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-flux/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-flux/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-flux/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-flux/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-flux/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-flux/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-flux/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-flux/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-flux/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-flux/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-flux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-flux/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-flux/build/test-report.html](https://npmtest.github.io/node-npmtest-react-flux/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-flux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-flux/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-flux/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-flux/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-flux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-flux/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-flux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-flux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Khaled Jouda"
    },
    "bugs": {
        "url": "https://github.com/kjda/ReactFlux/issues"
    },
    "dependencies": {
        "lodash": "^3.10.1",
        "promise": "^7.0.1"
    },
    "description": "A library implementing React Flux data flow",
    "devDependencies": {
        "chai": "^2.2.0",
        "colors": "^1.0.3",
        "commander": "^2.7.1",
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.13",
        "mocha": "^2.2.4",
        "sinon": "^1.14.1",
        "underscore": "^1.8.3",
        "webpack": "^1.9.10"
    },
    "directories": {},
    "dist": {
        "shasum": "eb19f465a626a91edcf887b08c8df71a576fb300",
        "tarball": "https://registry.npmjs.org/react-flux/-/react-flux-1.0.1.tgz"
    },
    "gitHead": "a0984cf01a7322f0b3e748509fe6661f1656abe4",
    "homepage": "https://github.com/kjda/ReactFlux",
    "keywords": [
        "React",
        "Flux",
        "ReactJS"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "khaled.jouda"
        }
    ],
    "name": "react-flux",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kjda/ReactFlux.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha -G",
        "test-cov": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec"
    },
    "version": "1.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
