
# Private-ID.js
WebAssembly + JavaScript bindings for the Private-ID protocol

## Usage

```JavaScript
// Test and bind the Private-ID Wasm binary

var privateid = {lib: {}, version: '1.0.0'};
let canary = canaries(privateid, 'https://github.com/nthparty/private-id-dist/releases/download/1.0.0/privateid.wasm');
canary([10, 9, 8, 4, 5, 6, 7, 3, 2, 1], 'permute', [[9, 8, 7], [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]]);
```
