# pathchop

## Install

```
npm install pathchop
```

## Usage

```javascript
var pathchop = require('pathchop');

pathchop('/a/b/c');
// {
//   file: 'c',
//   dir: '/a/b/'
// }

pathchop('/a/b/c/');
// {
//   file: null,
//   dir: '/a/b/c/'
// }
```
