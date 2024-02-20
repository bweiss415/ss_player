# ss_player

This project integrates a WebAssembly (Wasm) module for efficient bid lookup directly within a video player, enhancing ad selection and optimization in real-time.

## Installation

Install the wasm packge with npm: https://www.npmjs.com/package/wasm-bid-lookup

```bash
npm install wasm-bid-lookup
```

In the ```/playerJS/frstrOSd_14.js``` file, ensure that the package is imported at the top of the script.

```javascript
import * as wasm from 'wasm-bid-lookup';
```

And then initialized
```
async function init() {
  await wasm.init(); // Initialize the WebAssembly module
  // Your code to use the wasm module
}
init();
```

## License

## Acknowledgments
Springserve
