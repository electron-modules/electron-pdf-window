# electron-pdf-window

[![electron modules][electron-modules-image]][electron-modules-url]

[electron-modules-image]: https://img.shields.io/badge/electron-modules-blue.svg
[electron-modules-url]: https://github.com/xudafeng/electron-modules

view PDF files in electron browser windows. this module adds support for viewing
PDF files in electron [`BrowserWindow`s](http://electron.atom.io/docs/api/browser-window/).
it works even if you navigate to a PDF file from a site, or opening a PDF file in
a new window. a `PDFWindow` instance is just a subclass of `BrowserWindow` so it
can be used just like it.
