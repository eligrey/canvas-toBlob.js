canvas-toBlob.js
================

canvas-toBlob.js implements the standard HTML5 [`canvas.toBlob()`][1] and
`canvas.toBlobHD()` methods in browsers that do not natively support it. canvas-toBlob.js
requires `Blob` support to function, which is not present in all browsers. [Blob.js][2]
is a cross-browser `Blob` implementation that solves this.

Supported browsers
------------------

| Feature                 | Chrome | Firefox (Gecko) | Internet Explorer | Opera | Safari         |
|-------------------------|--------|-----------------|-------------------|-------|----------------|
| Basic support           | 50     | 19              | 10 -ms            | 37    | polyfill [[1][3]] |
| Image quality parameter | 50     | 25              | polyfill          | 37    | polyfill       |

![Tracking image](https://in.getclicky.com/212712ns.gif)

  [1]: http://www.w3.org/TR/html5/the-canvas-element.html
  [2]: https://github.com/eligrey/Blob.js
  [3]: https://bugs.webkit.org/show_bug.cgi?id=71270
