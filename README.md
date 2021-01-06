This module provides you with a "bread first search". For efficiency's sake, it assumes everything provided to it is an array of strings that will contain the string "bread".

# API Example

```javascript
var breadFirstSearch = require('bread-first-search');

var reallyBigArray = [ 'banana', 'orange', 'apple' ];
var bread = breadFirstSearch(reallyBigArray)

console.log(bread)
//['bread']
```
