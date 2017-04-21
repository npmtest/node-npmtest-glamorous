# npmtest-glamorous

#### basic test coverage for  [glamorous (v3.9.2)](https://github.com/paypal/glamorous#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-glamorous.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-glamorous) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-glamorous.svg)](https://travis-ci.org/npmtest/node-npmtest-glamorous)

#### React component styling solved

[![NPM](https://nodei.co/npm/glamorous.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/glamorous)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-glamorous/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-glamorous/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-glamorous/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-glamorous/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-glamorous/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-glamorous/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-glamorous/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-glamorous/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-glamorous/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-glamorous/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-glamorous/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-glamorous/build/test-report.html](https://npmtest.github.io/node-npmtest-glamorous/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-glamorous/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-glamorous/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-glamorous/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-glamorous/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-glamorous/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-glamorous/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-glamorous/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-glamorous/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "glamorous",
    "version": "3.9.2",
    "description": "React component styling solved",
    "main": "dist/glamorous.cjs.js",
    "jsnext:main": "dist/glamorous.es.js",
    "module": "dist/glamorous.es.js",
    "typings": "typings/glamorous.d.ts",
    "scripts": {
        "start": "nps",
        "test": "nps test",
        "test:ts": "tsc -p ./tsconfig.json",
        "commitmsg": "opt --in commit-msg --exec \"validate-commit-msg\"",
        "precommit": "lint-staged && opt --in pre-commit --exec \"npm start validate\""
    },
    "files": [
        "dist",
        "typings"
    ],
    "keywords": [
        "react",
        "css",
        "css-in-js",
        "styled-components",
        "glamor",
        "jsxstyle"
    ],
    "author": "Kent C. Dodds <kent@doddsfamily.us> (http://kentcdodds.com/)",
    "license": "MIT",
    "dependencies": {
        "brcast": "^2.0.0",
        "fast-memoize": "^2.2.7",
        "html-tag-names": "^1.1.1",
        "react-html-attributes": "^1.2.2",
        "svg-tag-names": "^1.1.0"
    },
    "peerDependencies": {
        "glamor": ">=2",
        "react": ">=14"
    },
    "devDependencies": {
        "@types/react": "^15.0.21",
        "all-contributors-cli": "^4.3.0",
        "babel-cli": "^6.24.1",
        "babel-jest": "^19.0.0",
        "babel-plugin-external-helpers": "^6.22.0",
        "babel-preset-env": "^1.4.0",
        "babel-preset-react": "^6.24.1",
        "babel-preset-stage-2": "^6.24.1",
        "babel-register": "^6.24.1",
        "codecov": "^2.1.0",
        "commitizen": "^2",
        "common-tags": "^1.4.0",
        "cz-conventional-changelog": "^2.0.0",
        "enzyme": "^2.8.2",
        "enzyme-to-json": "^1.5.1",
        "eslint": "^3.17.0",
        "eslint-config-kentcdodds": "^12.0.0",
        "glamor": "^2.20.24",
        "husky": "^0.13.2",
        "jest-cli": "^19.0.2",
        "jest-glamor-react": "^1.2.0",
        "lint-staged": "^3.3.1",
        "nps": "^5.0.6",
        "nps-utils": "^1.1.2",
        "opt-cli": "^1.5.1",
        "prettier-eslint-cli": "^3.3.0",
        "prop-types": "^15.5.8",
        "react": "^15.5.4",
        "react-addons-test-utils": "^15.5.1",
        "react-dom": "^15.5.4",
        "react-test-renderer": "^15.5.4",
        "rollup": "^0.41.6",
        "rollup-plugin-babel": "^2.7.1",
        "rollup-plugin-commonjs": "^8.0.2",
        "rollup-plugin-json": "^2.1.1",
        "rollup-plugin-node-resolve": "^3.0.0",
        "rollup-plugin-replace": "^1.1.1",
        "rollup-plugin-uglify": "^1.0.1",
        "semantic-release": "^6.3.6",
        "tslint": "^5.1.0",
        "tslint-microsoft-contrib": "^4.0.1",
        "typescript": "^2.2.2",
        "validate-commit-msg": "^2.12.1"
    },
    "eslintConfig": {
        "extends": [
            "kentcdodds",
            "kentcdodds/jest",
            "kentcdodds/react",
            "kentcdodds/prettier"
        ],
        "rules": {
            "import/prefer-default-export": 0
        }
    },
    "lint-staged": {
        "*.js": [
            "prettier-eslint --write",
            "git add"
        ]
    },
    "jest": {
        "testEnvironment": "jsdom",
        "coverageThreshold": {
            "global": {
                "branches": 100,
                "functions": 100,
                "lines": 100,
                "statements": 100
            }
        },
        "snapshotSerializers": [
            "enzyme-to-json/serializer"
        ],
        "roots": [
            "src"
        ]
    },
    "config": {
        "commitizen": {
            "path": "node_modules/cz-conventional-changelog"
        }
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/paypal/glamorous.git"
    },
    "bugs": {
        "url": "https://github.com/paypal/glamorous/issues"
    },
    "homepage": "https://github.com/paypal/glamorous#readme"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
