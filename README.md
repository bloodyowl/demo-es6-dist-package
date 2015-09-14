# demo-es6 dist package

## output

```javascript
"use strict";

Object.defineProperty(exports, "__esModule", {
  value: true
});

function _interopRequireDefault(obj) { return obj && obj.__esModule ? obj : { "default": obj }; }

var _lodash = require("lodash");

var _lodash2 = _interopRequireDefault(_lodash);

var logForEach = function logForEach(collection) {
  return _lodash2["default"].forEach(collection, console.log.bind(console));
};

exports.logForEach = logForEach;
```
