# Simplifier.js
Simplifoer.js was a package that made to simplified NodejS Code
How to import in NodejS v13 and below
```js
require('simplifier.js');
```
or
```js
const simple = require('simplifier.js');
```
How to import in NodejS v14 and above
```js
import 'simplifier.js';
```
## Example: 
```js
require('simplifier.js');
        console.log(random());
        // RANDOM NUMBER BETWEEN 0 - 10
        console.log(random(null, 30))
        // RANDOM NUMBER BETWEEN -30 - 30
        console.log(random(5))
        // RANDOM NUMBR BETWEEN 5 - 10
        console.log(random(10, 50))
        // RANDOM NUMBER BETWEEN 10 - 50
```
```js
const simple = require('simplifier.js');
        console.log(simple.random());
        // RANDOM NUMBER BETWEEN 0 - 10
        console.log(simple.random(null, 30))
        // RANDOM NUMBER BETWEEN -30 - 30
        console.log(simple.random(5))
        // RANDOM NUMBR BETWEEN 5 - 10
        console.log(simple.random(10, 50))
        // RANDOM NUMBER BETWEEN 10 - 50
```
## Importing choosen function only
```js
const { consoleError } = require('simplifier.js');
consoleError('Something was wrong'); // Return 'Somehing was wrong' on red color
random(1, 14); // Return Typescript Error (Function not found)
