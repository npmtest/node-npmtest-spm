# npmtest-spm

#### basic test coverage for  [spm (v3.6.12)](http://spmjs.io)  [![npm package](https://img.shields.io/npm/v/npmtest-spm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-spm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-spm.svg)](https://travis-ci.org/npmtest/node-npmtest-spm)

#### Static Package Manager

[![NPM](https://nodei.co/npm/spm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-spm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-spm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-spm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-spm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-spm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-spm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-spm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-spm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-spm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-spm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-spm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-spm/build/test-report.html](https://npmtest.github.io/node-npmtest-spm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-spm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-spm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-spm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-spm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-spm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hsiaoming Yang"
    },
    "bin": {
        "spm": "bin/spm"
    },
    "bugs": {
        "url": "https://github.com/spmjs/spm/issues"
    },
    "dependencies": {
        "archy": "~1.0.0",
        "babel-core": "~4.7.16",
        "chokidar": "~1.0.3",
        "co": "~4.6.0",
        "colorful": "~2.1.0",
        "commander": "~2.5.0",
        "crequire": "~1.5.3",
        "debug": "^2.1.1",
        "empty-dir": "~0.1.0",
        "exeq": "~2.0.0",
        "extend": "~2.0.0",
        "father": "~1.0.0",
        "fs-extra": "~0.13.0",
        "fs-symlink": "1.1.0",
        "fstream": "~1.0.3",
        "fstream-ignore": "~1.0.2",
        "glob": "~5.0.12",
        "gnode": "~0.1.1",
        "gulp-template": "~1.1.1",
        "inherits": "~1.0.0",
        "inquirer": "~0.8.0",
        "internal-ip": "~1.0.0",
        "istanbul": "~0.3.5",
        "istanbul-instrumenter-loader": "~0.1.2",
        "mocha-phantomjs": "3.5.6",
        "nico-spm": "~0.5.2",
        "phantomjs": "~1.9.1",
        "react-tools": "~0.12.2",
        "request": "~2.51.0",
        "rimraf": "~2.2.8",
        "scripts-hook": "~0.1.3",
        "semver": "~4.1.0",
        "sort-array": "~0.1.0",
        "spm-client": "~0.4.0",
        "spm-log": "~0.1.1",
        "spm-webpack": "~0.7.0",
        "spm-webpack-server": "~0.7.0",
        "spmrc": "~1.2.0",
        "tar": "~1.0.3",
        "test-console": "~0.7.1",
        "through2": "~2.0.0",
        "uniq": "~1.0.1",
        "vinyl-fs": "~0.3.13",
        "whoami": "~0.0.3",
        "win-spawn": "~2.0.0"
    },
    "description": "Static Package Manager",
    "devDependencies": {
        "coveralls": "~2.11.2",
        "gulp-unzip": "~0.1.1",
        "jshint": "*",
        "ls-archive": "~1.0.2",
        "mocha": "*",
        "muk": "~0.3.1",
        "should": "~4.3.1",
        "sinon": "~1.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9fdddafaefa974cac8ad6581fe40f2c7a3d546da",
        "tarball": "https://registry.npmjs.org/spm/-/spm-3.6.12.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "4da55f553d3437ec90ac09b74922b663facfff6f",
    "homepage": "http://spmjs.io",
    "keywords": [
        "bower",
        "browser",
        "cmd",
        "command line",
        "commonjs",
        "component",
        "module",
        "npm",
        "package",
        "seajs",
        "spmjs",
        "tool"
    ],
    "maintainers": [
        {
            "name": "afc163"
        },
        {
            "name": "kangpangpang"
        },
        {
            "name": "lepture"
        },
        {
            "name": "lifesinger"
        },
        {
            "name": "pigcan"
        },
        {
            "name": "popomore"
        },
        {
            "name": "sorrycc"
        },
        {
            "name": "yyfrankyy"
        }
    ],
    "name": "spm",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/spmjs/spm.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "3.6.12"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
