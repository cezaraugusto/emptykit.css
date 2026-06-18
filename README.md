[npm-version-image]: https://img.shields.io/npm/v/emptykit.css.svg?color=0971fe
[npm-version-url]: https://www.npmjs.com/package/emptykit.css
[npm-downloads-image]: https://img.shields.io/npm/dm/emptykit.css.svg?color=2ecc40
[npm-downloads-url]: https://www.npmjs.com/package/emptykit.css
[action-image]: https://github.com/cezaraugusto/emptykit.css/actions/workflows/ci.yml/badge.svg?branch=main
[action-url]: https://github.com/cezaraugusto/emptykit.css/actions

> Specific CSS reset for Webkit/Chromium based apps

# emptykit.css [![Version][npm-version-image]][npm-version-url] [![Downloads][npm-downloads-image]][npm-downloads-url] [![workflow][action-image]][action-url]

<img src="https://raw.githubusercontent.com/cezaraugusto/emptykit.css/master/logo.png" align="right" width="130px" height="130px"/>

`emptykit` is a CSS reset specific for Webkit/Chromium apps such as Electron, Muon, Chrome extensions and websites that rely solely on browsers using those technologies (Chrome, Brave, Safari, and Opera).

<hr>

## Install

```sh
npm install emptykit.css
```

**Other methods**

* [CDN (unpkg, jsDelivr)](https://www.jsdelivr.com/package/npm/emptykit.css)
* [Download](https://github.com/cezaraugusto/emptykit.css/blob/master/emptykit.css)

## Usage

Import it once at your app's entry point:

```js
import 'emptykit.css'
```

Or reference it directly from HTML:

```html
<link rel="stylesheet" href="node_modules/emptykit.css/emptykit.css" />
```

## Why should you use this?

If you develop applications for Webkit/Chromium there's no need to have additional resets for platforms that you'll never need.

## Differences between other CSS resets.

`emptykit` is specific for Webkit/Chromium-dependent apps and while it can work well using other technologies, they were not tested nor will be as `emptykit` was designed specificaly for them.

If you need to support other engines, [normalize.css](https://github.com/necolas/normalize.css/) or [sanitize.css](https://github.com/jonathantneal/sanitize.css/) might be better suitable for you.

## Support

| <img src="https://github.com/gilbarbara/logos/blob/master/logos/brave.svg" width="100"> | <img src="https://github.com/gilbarbara/logos/blob/master/logos/chrome.svg" width="100"> |  <img src="https://github.com/gilbarbara/logos/blob/master/logos/electron.svg" width="100"> | <img src="https://github.com/gilbarbara/logos/blob/master/logos/opera.svg" width="100"> | <img src="https://github.com/gilbarbara/logos/blob/master/logos/safari.svg" width="100"> |
|-------|-------|-------|-------|-------|
|  All  |   51  | 1.3.0 |   38  |   9   |

## Contributing

Please open an issue or pull request if there's something you'd like to propose/change.

## License

MIT (c) Cezar Augusto.
