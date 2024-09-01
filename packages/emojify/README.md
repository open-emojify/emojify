<p align="center">
<img alt="Logo Banner" src="https://raw.githubusercontent.com/open-emojify/emojify/main/banner/banner.svg?sanitize=true"/>
<br/>

[![Published on npm](https://img.shields.io/npm/v/open-emojify)](https://www.npmjs.com/package/open-emojify)
[![](https://data.jsdelivr.com/v1/package/npm/open-emojify/badge)](https://www.jsdelivr.com/package/npm/open-emojify)
<!--[![npm Downloads](https://img.shields.io/npm/dm/open-emojify?label=npm%20downloads)](https://npm-stat.com/charts.html?package=open-emojify)-->

<div align="left">Emojify is a customizable emoji trail javascript library that follows your mouse cursor, embedding playfulness and personality into any webpage.</div>
<div align="left">

[Demo](https://open-emojify.github.io/emojify/)  

## Installation

### CDN

Import Emojify using CDN.

```index.html```

```html
<script src="https://cdn.jsdelivr.net/npm/open-emojify/emojify.min.js"></script>
```

#### 🚧 Specific Version
```html
<script src="https://cdn.jsdelivr.net/npm/open-emojify@0.0.15/emojify.min.js"></script>
```

## Usage

Call the Emojify library in your Javascript. That's it 🎉.

```main.js```

```js
window.emojify = new Emojify({});
```

## Customization

Emojify comes with options / variables that can easily be customized.

```js
window.emojify = new Emojify({
    emojis: ['😂','😎','😍','😀'], // replaces default emojis with emojis within a string
    random: true, // determines if emojis should be shown random or in order
    duration: 500, // duration before hiding emojis
    delay: 15, // delay between showing a new emoji
    size: '48px', // font-size of emojis
    zIndex: 9999, // z-index of emojis
});
```

Check out the Demo on [Codepen.](https://codepen.io/GreenestGoat/pen/gONGbBo?editors=0010)

Emojify is also a [Chrome Extension.](https://github.com/open-emojify/emojify-extension)

## Copyright and license

Licensed under the MIT License, Copyright © 2024-present Emojify.

See [LICENSE](https://github.com/open-emojify/emojify/blob/main/LICENSE) for more information.
