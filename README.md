### ripple-graph
---
https://github.com/ripple-unmaintained/ripple-graph

```js
// sha1.js
Utf8.decode = function(strUtf) {
  
  var strUni = strUtf.replace(
    //g,
    function(c) {
      var cc = ((c.charCodeAt(0)&0xof)<<12) | ((c.charCodeAt(1)&0x3f)<<6) | ( c.charCodeAt(2)&0x3f);
      return String.fromCharCode(cc); }
  );
  strUni = strUni.replace(
    //g,
    function(c) {
      var cc = (c.charCodeAt(0)&0x1f)&0x3f;
      return String.fromCharCode(cc); }
  );
  return strUni;
}
```

```
```

```
```


