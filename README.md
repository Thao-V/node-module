# node-module: (Tested with Node v18.14.2)
## CommonJS: 
* Import a module: const lib = require('path-to-lib')
## Module: Using import for third party modules or built-in modules
* Import a module: import lib from 'path-to-lib';
* Add to package.json: "type": "module"
## ES6: 
* Import a module: import lib from 'path-to-lib';
* Export a module: export default lib
* Install and run: npm i & npm start