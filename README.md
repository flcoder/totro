# Totro, the Fantasy Random Name Generator
A port of David A. Wheeler's Totro for use as a library.
http://www.dwheeler.com/totro.html
## Usage

Node: `npm install totro`
```javascript
var totro = require('totro');
console.log( totro.RandomName(2,5) );
```

Browser: `<script src="totro/index.js"></script>`, window.totro object is available
```javascript
var name = totro.RandomName(2,5);
```


