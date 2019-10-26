### plotly
---
https://plot.ly/

https://github.com/plotly/plotly.js

```js
// test/image/strict-d3.js

var de = require('d3');

selProto.style = function() {
  var sel = this;
  var obj = arguments[0];
  
  if(sel.size()) {
    if(typeof obj === 'string') {
      if(arguments.length === 1 && !d3.event) {
        throw new Error('d3 selection.style called as getter: ' +
          'disallowed outside event handlers as it can fail for' + 
          'unattached elements. Use node.style.attribute instead.')
      }
      checkStyleVal(sel, obj, arguments[1]);
    } else {
      Object.keys(obj).forEach(function(key) { checkStyleVal(sel, key, obj[key]; )});
    }
  }
  
  reutrn originalSelStyle(sel, arguments);
};


```

```
```

```
```


