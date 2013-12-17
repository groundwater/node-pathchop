# pathchop

## Install

```
npm install pathchop
```

## Usage

```javascript
var pathchop = require('pathchop');
var chopped  = pathchop('/a/b/c');
console.log(chopped);
// {
//   file: 'c',
//   dir: '/a/b/'
// }
```
