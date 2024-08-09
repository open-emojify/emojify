<p align="center">
<img alt="Logo Banner" src="https://raw.githubusercontent.com/open-emojify/emojify/main/banner/banner.svg?sanitize=true"/>
<br/>

<div align="left">Emojify is a customizable emoji trail javascript library that follows your mouse cursor, embedding playfulness and personality into any webpage.</div>
<div align="left">

[Demo](https://open-emojify.github.io/emojify/)

## Installation

### CDN

Import Emojify using CDN.

```index.js```

```js
import Emojify from 'https://cdn.jsdelivr.net/npm/open-emojify/emojify.min.js';
```

#### 🚧 Specific Version
```js
import Emojify from 'https://cdn.jsdelivr.net/npm/open-emojify/emojify.min.js@latest';
```

## Usage

Call the Emojify library in your Javascript. That's it 🎉.

```index.js```

```js
new Emojify({});
```

## Customization

Emojify comes with default options that can easily be customized.

```js
new Emojify({
    emojis: ['😊','😄','😀','😃'], // replaces the default emojis with the emojis within the string.
    random: true, // determines wether emojis should be shown as random or in order.
    duration: 500, // duration before hiding emojis.
    delay: 5, // delay between showing a new emoji.
    size: '48px', // font-size of emojis.
    zIndex: 9999, // z-index of emojis
});
```