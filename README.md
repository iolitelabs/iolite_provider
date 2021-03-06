## iolite-provider

A simple provider module for the iOlite (compatible with Ethereum) RPC layer.

## Install

```
npm install --save iolite-provider
```

## Usage

```js
const Web3 = require('web3')
const Eth = require('ethjs')

const IoliteProvider = require('iolite-provider')
const provider = new IoliteProvider('https://sia.node.iolite.io', '0xecbcd9838f7f2afa6e809df8d7cdae69aa5dfc14d563ee98e97effd3f6a652f2')
const eth = new Eth(provider)
const web3 = new Web3(provider)

});
```

## About

A simple provider module for the HTTP protocol that follows the web3 provider specification. This is purely an HTTP bypass using the XHR2 module.
