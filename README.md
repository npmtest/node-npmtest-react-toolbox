# npmtest-react-toolbox

#### basic test coverage for  [react-toolbox (v2.0.0-beta.8)](http://www.react-toolbox.com)  [![npm package](https://img.shields.io/npm/v/npmtest-react-toolbox.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-toolbox) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-toolbox.svg)](https://travis-ci.org/npmtest/node-npmtest-react-toolbox)

#### A set of React components implementing Google's Material Design specification with the power of CSS Modules.

[![NPM](https://nodei.co/npm/react-toolbox.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-toolbox)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-toolbox/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-toolbox/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-toolbox/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-toolbox/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-toolbox/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-toolbox/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-toolbox/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-toolbox/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-toolbox/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-toolbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-toolbox/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-toolbox/build/test-report.html](https://npmtest.github.io/node-npmtest-react-toolbox/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-toolbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-toolbox/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-toolbox/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-toolbox/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-toolbox/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-toolbox/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-toolbox/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-toolbox/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-toolbox",
    "description": "A set of React components implementing Google's Material Design specification with the power of CSS Modules.",
    "homepage": "http://www.react-toolbox.com",
    "version": "2.0.0-beta.8",
    "main": "./lib",
    "author": {
        "name": "Javier Velasco Arjona",
        "url": "http://javivelasco.com/"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/react-toolbox/react-toolbox.git"
    },
    "bugs": {
        "url": "https://github.com/react-toolbox/react-toolbox/issues"
    },
    "keywords": [
        "components",
        "material design",
        "react",
        "react-component",
        "toolkit"
    ],
    "dependencies": {
        "classnames": "^2.2.5",
        "core-js": "^2.4.0",
        "ramda": "^0.23.0",
        "react-addons-css-transition-group": "^15.4.2",
        "react-css-themr": "^1.7.2",
        "react-style-proptype": "^2.0.0"
    },
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.10",
        "babel-plugin-react-transform": "^2.0.2",
        "babel-polyfill": "^6.22.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react": "^6.22.0",
        "babel-preset-stage-0": "^6.22.0",
        "cpx": "^1.5.0",
        "cross-env": "^3.1.3",
        "css-loader": "^0.26.1",
        "enzyme": "^2.7.1",
        "enzyme-to-json": "^1.4.5",
        "eslint": "^3.15.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-import-resolver-webpack": "^0.8.1",
        "eslint-plugin-babel": "^4.0.1",
        "eslint-plugin-compat": "^1.0.1",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.9.0",
        "express": "^4.14.1",
        "extract-text-webpack-plugin": "~2.0.0-rc.3",
        "git-dirty": "^1.0.2",
        "glob": "^7.1.1",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-postcss": "^6.3.0",
        "gulp-rimraf": "^0.2.1",
        "identity-obj-proxy": "^3.0.0",
        "internal-ip": "^1.2.0",
        "jest": "^18.1.0",
        "lint-staged": "^3.3.0",
        "mocha": "^3.1.2",
        "normalize.css": "^5.0.0",
        "postcss-cssnext": "^2.8.0",
        "postcss-each": "^0.9.3",
        "postcss-import": "^9.1.0",
        "postcss-loader": "^1.2.2",
        "postcss-mixins": "^5.4.0",
        "postcss-reporter": "^3.0.0",
        "pre-commit": "^1.2.2",
        "react": "^15.4.2",
        "react-addons-test-utils": "^15.4.2",
        "react-dom": "^15.4.2",
        "react-test-renderer": "^15.4.2",
        "react-transform-catch-errors": "^1.0.2",
        "react-transform-hmr": "^1.0.4",
        "redbox-react": "^1.3.2",
        "rimraf": "^2.5.2",
        "style-loader": "^0.13.1",
        "stylelint": "^7.8.0",
        "stylelint-config-standard": "^16.0.0",
        "stylelint-order": "^0.2.2",
        "webpack": "~2.2.0",
        "webpack-dev-middleware": "^1.10.0",
        "webpack-hot-middleware": "^2.16.1"
    },
    "engines": {
        "node": ">= 6"
    },
    "scripts": {
        "babel": "babel ./components --out-dir ./lib",
        "build": "cross-env NODE_ENV=production gulp && npm run tsd",
        "clean": "rimraf ./lib",
        "css": "cpx \"./components/**/*.css\" ./lib",
        "lint": "npm run lint:js && npm run lint:css",
        "lint:css": "stylelint ./components/**/*.css",
        "lint:js": "eslint ./ --ext .js",
        "lint:staged": "lint-staged",
        "patch": "bumped release patch",
        "prebuild": "npm run clean",
        "prepublish": "npm run build",
        "release": "bumped release",
        "start": "cross-env NODE_ENV=development UV_THREADPOOL_SIZE=100 node ./server",
        "test": "jest",
        "test:watch": "jest --watch --no-watchman",
        "tsd": "cpx \"./components/**/*.d.ts\" ./lib"
    },
    "license": "MIT",
    "jest": {
        "moduleDirectories": [
            "node_modules"
        ],
        "moduleNameMapper": {
            "(\\.css$)|(normalize.css/normalize)|(^exports-loader)": "identity-obj-proxy"
        },
        "modulePaths": [
            "<rootDir>"
        ],
        "setupFiles": [
            "./jest.config.js"
        ],
        "snapshotSerializers": [
            "enzyme-to-json/serializer"
        ]
    },
    "peerDependencies": {
        "classnames": "^2.2.0",
        "react": "^0.14 || ~15.4.0",
        "react-addons-css-transition-group": "^0.14.0 || ~15.4.0",
        "react-dom": "^0.14.0 || ~15.4.0"
    },
    "pre-commit": "lint:staged",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
