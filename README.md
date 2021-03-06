# npmdoc-moment-range

#### basic api documentation for  [moment-range (v3.0.3)](https://github.com/gf3/moment-range)  [![npm package](https://img.shields.io/npm/v/npmdoc-moment-range.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-moment-range) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-moment-range.svg)](https://travis-ci.org/npmdoc/node-npmdoc-moment-range)

#### Fancy date ranges for Moment.js

[![NPM](https://nodei.co/npm/moment-range.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/moment-range)

- [https://npmdoc.github.io/node-npmdoc-moment-range/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-moment-range/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-moment-range/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-moment-range/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-moment-range/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-moment-range/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gianni Chiappetta",
        "url": "https://butt.zone"
    },
    "bugs": {
        "url": "https://github.com/gf3/moment-range/issues"
    },
    "contributors": [
        {
            "name": "Adam Biggs",
            "url": "lightmaker.com"
        },
        {
            "name": "Mats Julian Olsen",
            "url": "https://github.com/mewwts"
        },
        {
            "name": "Matt Patterson",
            "url": "http://reprocessed.org/"
        },
        {
            "name": "Wilgert Velinga",
            "url": "http://neocles.io"
        },
        {
            "name": "Tomasz Bak",
            "url": "http://twitter.com/tomaszbak"
        },
        {
            "name": "Stuart Kelly",
            "url": "https://github.com/stuartleigh"
        },
        {
            "name": "Jeremy Forsythe",
            "url": "https://github.com/jdforsythe"
        },
        {
            "name": "Александр Гренишин",
            "url": "https://github.com/nd0ut"
        },
        {
            "name": "@scotthovestadt",
            "url": "https://github.com/scotthovestadt"
        },
        {
            "name": "Thomas van Lankveld",
            "url": "https://github.com/thomasvanlankveld"
        },
        {
            "name": "nebel",
            "url": "https://github.com/pronebel"
        },
        {
            "name": "Kevin Ross",
            "url": "http://www.alienfast.com"
        },
        {
            "name": "Thomas Walpole",
            "url": "https://github.com/twalpole"
        },
        {
            "name": "Jonathan Kim",
            "url": "jkimbo.co.uk"
        },
        {
            "name": "Tymon Tobolski",
            "url": "http://teamon.eu"
        },
        {
            "name": "Aristide Niyungeko",
            "url": "https://github.com/aristiden7o"
        },
        {
            "name": "Bradley Ayers",
            "url": "https://github.com/bradleyayers"
        },
        {
            "name": "Ross Hadden",
            "url": "http://rosshadden.github.com/resume"
        },
        {
            "name": "Victoria French",
            "url": "https://github.com/victoriafrench"
        },
        {
            "name": "Jochen Diekenbrock",
            "url": "https://github.com/JochenDiekenbrock"
        }
    ],
    "dependencies": {
        "es6-symbol": "^3.1.0"
    },
    "description": "Fancy date ranges for Moment.js",
    "devDependencies": {
        "babel-core": "^6.18.2",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.8",
        "babel-plugin-transform-flow-strip-types": "^6.18.0",
        "babel-polyfill": "^6.16.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-stage-0": "^6.16.0",
        "doctoc": "^1.2.0",
        "eslint": "^3.11.1",
        "eslint-loader": "^1.6.1",
        "expect.js": "^0.3.1",
        "flow-bin": "^0.36.0",
        "karma": "^1.3.0",
        "karma-babel-polyfill": "0.0.5",
        "karma-chrome-launcher": "^2.0.0",
        "karma-expect": "^1.1.3",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^2.0.2",
        "mocha": "^2.5.3",
        "moment": "^2.17.1",
        "webpack": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f7a1567c73228f317469cb33148ea996f79ccb9a",
        "tarball": "https://registry.npmjs.org/moment-range/-/moment-range-3.0.3.tgz"
    },
    "engines": {
        "node": "*"
    },
    "files": [
        "dist/",
        "lib/"
    ],
    "gitHead": "c2474be0aa1fb3a46e914778af9788f1c18afe93",
    "homepage": "https://github.com/gf3/moment-range",
    "jsnext:main": "lib/moment-range.js",
    "license": {
        "type": "Public Domain",
        "url": "https://github.com/gf3/moment-range/raw/master/UNLICENSE"
    },
    "main": "./dist/moment-range",
    "maintainers": [
        {
            "name": "adambiggs"
        },
        {
            "name": "gf3"
        }
    ],
    "name": "moment-range",
    "optionalDependencies": {},
    "peerDependencies": {
        "moment": ">= 2"
    },
    "repository": {
        "type": "git",
        "url": "git+https://git@github.com/gf3/moment-range.git"
    },
    "scripts": {
        "build": "webpack",
        "doctoc": "doctoc README.md --github",
        "flow": "flow",
        "lint": "eslint ./lib/",
        "prepublish": "npm run build; cp ./declarations/moment-range.js.flow ./dist",
        "preversion": "npm run flow && npm run lint && npm run test",
        "test": "karma start ./karma.conf.js",
        "version": "npm run build; cp ./declarations/moment-range.js.flow ./dist"
    },
    "version": "3.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
