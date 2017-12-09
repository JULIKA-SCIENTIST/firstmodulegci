# firstmodulegci


## Installation 
```sh
npm install firstmodulegci --save

```

## Usage

### JavaScript

```javascript
var firstmodule = require('firstmodulegci');
var output = firstmodule.printMsg();
console.log(output);

```
```sh
Output should be 'Hello World - GCI 2017'

```



### AMD
```javascript
exports.printMsg= function()
{
	console.log("Hello World - GCI 2017");
};
```

## Test 
```sh
npm run test
```
