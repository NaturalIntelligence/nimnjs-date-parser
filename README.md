# nimnjs-date-parser
compress date for nimnjs


## Introduction
See Nimn [specification](https://github.com/nimndata/spec) for more detail.

## Usages
First install or add to your npm package
```
$npm install nimnjs-date-parser
```

```js
var nimn = require("nimnjs-date-parser");

var dt = new Date("Mon Feb 26 2018 17:42:17 GMT+0530 (IST)");
var nimnDt = parser.parse(dt,true,true,true);//Fqcchm
var dt2 = parser.parseBack(nimnDt,true,true,true);

```
