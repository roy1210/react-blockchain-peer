# Blockchain-Peer-JavaScript

## Description

This is peer code for [Blockchain-JavaScript]().

To deploy in Heroku as peered website to role as peered user. (P2P)


## Features

Changed `ROOT_NODE_ADDRESS` to hosting website for production.


index.js
```
const ROOT_NODE_ADDRESS = isDevelopment
  ? `http://localhost:${DEFAULT_PORT}`
  : "https://my-crypto-blockchain.herokuapp.com";
```

## Licence

[MIT](./LICENSE.txt)

## Author

[Shoe Kure](https://github.com/roy1210)
