# npmdoc-httpp-proxy

#### api documentation for  [httpp-proxy (v0.10.3)](https://github.com/InstantWebP2P/node-httpp-proxy#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-httpp-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-httpp-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-httpp-proxy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-httpp-proxy)

#### A full-featured httpp reverse proxy for node.js

[![NPM](https://nodei.co/npm/httpp-proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/httpp-proxy)

- [https://npmdoc.github.io/node-npmdoc-httpp-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-httpp-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-httpp-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-httpp-proxy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-httpp-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-httpp-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bin": {
        "node-http-proxy": "./bin/node-http-proxy"
    },
    "bugs": {
        "url": "https://github.com/InstantWebP2P/node-httpp-proxy/issues"
    },
    "dependencies": {
        "colors": "0.x.x",
        "optimist": "0.3.x",
        "pkginfo": "0.2.x",
        "utile": "~0.1.7"
    },
    "description": "A full-featured httpp reverse proxy for node.js",
    "devDependencies": {
        "async": "0.2.x",
        "request": "2.14.x",
        "socket.io": "0.9.11",
        "socket.io-client": "0.9.11",
        "vows": "0.7.x",
        "wspp": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "a01b1e6ac543002a115c79dd57bcf4cb2f822b8f",
        "tarball": "https://registry.npmjs.org/httpp-proxy/-/httpp-proxy-0.10.3.tgz"
    },
    "engines": {
        "node": ">= 0.6.6"
    },
    "homepage": "https://github.com/InstantWebP2P/node-httpp-proxy#readme",
    "keywords": [
        "reverse",
        "proxy",
        "http",
        "httpp",
        "peer",
        "p2p"
    ],
    "main": "./lib/node-http-proxy",
    "maintainers": [
        {
            "name": "iwebpp"
        }
    ],
    "name": "httpp-proxy",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git://github.com/InstantWebP2P/node-httpp-proxy.git"
    },
    "scripts": {
        "test": "npm run-script test-http && npm run-script test-https && npm run-script test-core",
        "test-core": "test/core/run",
        "test-http": "vows --spec && vows --spec --target=https",
        "test-https": "vows --spec --proxy=https && vows --spec --proxy=https --target=https"
    },
    "version": "0.10.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
