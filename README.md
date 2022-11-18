# TinyView.js
> TinyView.js is a lightweight javascript Image Viewer

[![Version](https://img.shields.io/npm/v/tinyview.js.svg)](https://www.npmjs.com/package/tinyview.js) 
[![Gzip Size](https://img.shields.io/bundlephobia/minzip/tinyview.js.svg)](https://unpkg.com/tinyview.js@1.0.3/tinyview.min.js)

## Features Demo
<img src="https://github.com/jacksonCV1114/TinyView/blob/main/Demo1.gif" width="300"/>
<img src="https://github.com/jacksonCV1114/TinyView/blob/main/Demo2.gif" width="300"/>
<img src="https://github.com/jacksonCV1114/TinyView/blob/main/Demo3.gif" width="300"/>

## Features
* Zoom In
* Zoom Out
* Left Rotation
* Right Rotation
* Move Image

## Main Files and Descriptions
```
src/
├── tinyview.css       (uncompressed)
├── tinyview.min.css   (compressed)
├── tinyview.js        (uncompressed)
└── tinyview.min.js    (compressed)
```

```
jsdoc/
├── ....
├── TinyView.html       (Documentation generated by Jsdoc)
└── tinyview.js.html    (Source code generated by Jsdoc)
```

## Getting Started

### Installation

NPM
```
npm install tinyview.js
```
In browser:
```
<link  href="/path/to/tinyview.css" rel="stylesheet">
<script src="/path/to/tinyview.js"></script>
```
### Example
```
<html>
    <body>
        <img width="200px" id="elem1" src="./image1.jpg">
        <img width="200px" id="elem2" src="./image2.jpg">
    </body>
  
    <script>
        const elem1 = document.getElementById("elem1");
        const elem2 = document.getElementById("elem2");
        const tinyview = new TinyView(elem1, elem2);
    </script>
</html>
```

