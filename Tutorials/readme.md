# HTML5 Shim vs. Shiv
<a href="http://stackoverflow.com/questions/14429061/html5-shim-vs-shiv">HTML5 Shim vs. Shiv</a>


[Trim Polyfill](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/Trim)

```js
if (!String.prototype.trim) {
  String.prototype.trim = function () {
    return this.replace(/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g, '');
  };
}
``` 

