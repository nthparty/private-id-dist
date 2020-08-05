# private-id-dist
WebAssembly + JavaScript bindings for the Private-ID protocol

# Usage
```JavaScript
/* Test and bind the Private-ID Wasm binary */
var privateid = {lib: {}, version: '1.0.0'};
let canary = canaries(privateid, './privateid.wasm');
canary([10, 9, 8, 4, 5, 6, 7, 3, 2, 1], 'permute', [[9, 8, 7], [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]]);
```
