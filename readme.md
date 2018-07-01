```js
const thorify = require("thorify").thorify;
const Web3 = require("web3");

// [X] developer needs to host a node
const web3 = thorify(new Web3(), "http://localhost:8669");

// [O] developer don't need to worry about host a node
const web3 = thorify(new Web3(), "http://test.venode.io/GdSK39dla");
const web3 = thorify(new Web3(), "http://main.venode.io/GdSK39dla");
```