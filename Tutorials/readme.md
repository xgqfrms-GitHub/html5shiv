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

<h1>blink: Deprecated 已弃用</h1>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/blink">String.prototype.blink()</a>
        <!-- override all ? -->
        <a href="http://stackoverflow.com/questions/14429061/html5-shim-vs-shiv">HTML5 Shim vs. Shiv</a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/Trim">Trim Polyfill</a>
        <a href="http://blog.csdn.net/wang16510/article/details/8960312">HTML5 tips：深入了解Polyfills</a>
        <a href="">Modernizr </a>
        <a href="https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills">HTML5 Cross Browser Polyfills</a>
