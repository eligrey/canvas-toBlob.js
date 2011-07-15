canvas-toBlob.js
================

canvas-toBlob.js implements the standard HTML5 [`canvas.toBlob()`][1] method in browsers that
do not natively support it. canvas-toBlob.js requires `BlobBuilder` support to function,
which is not present in all browsers. [BlobBuilder.js][2] is a cross-browser `BlobBuilder`
implementation that solves this.


  [1]: http://www.w3.org/TR/html5/the-canvas-element.html
  [2]: https://github.com/eligrey/BlobBuilder.js