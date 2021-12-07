# electron-pdf-window-alt

---

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/electron-pdf-window-alt.svg
[npm-url]: https://npmjs.org/package/electron-pdf-window-alt
[travis-image]: https://api.travis-ci.com/electron-modules/electron-pdf-window-alt.svg?branch=master
[travis-url]: https://travis-ci.com/github/electron-modules/electron-pdf-window-alt
[coveralls-image]: https://img.shields.io/coveralls/electron-modules/electron-pdf-window-alt.svg
[coveralls-url]: https://coveralls.io/r/electron-modules/electron-pdf-window-alt?branch=master
[node-image]: https://img.shields.io/badge/node.js-%3E=_8-green.svg
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/electron-pdf-window-alt.svg
[download-url]: https://npmjs.org/package/electron-pdf-window-alt

view PDF files in electron browser windows. this module adds support for viewing
PDF files in electron [`BrowserWindow`s](http://electron.atom.io/docs/api/browser-window/).
it works even if you navigate to a PDF file from a site, or opening a PDF file in
a new window. a `PDFWindow` instance is just a subclass of `BrowserWindow` so it
can be used just like it.
