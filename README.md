# 👢 Modress

A lightweight modular CSS reset designed to support older browsers and seamlessly integrate with Web Components, eliminating code duplication. It's essentially a modularization of [ress](https://github.com/filipelinhares/ress) with some enhancements borrowed from [modern-normalize](https://github.com/sindresorhus/modern-normalize). If you're initiating a new project that doesn't require legacy browser support or won't utilize Web Components, consider using [modern-normalize](https://github.com/sindresorhus/modern-normalize).

For more details, check out:
- [ress](https://github.com/filipelinhares/ress)
- [normalize.css](https://github.com/necolas/normalize.css)
- [normalize.css Know Issues](https://github.com/necolas/normalize.css#extended-details-and-known-issues)
- [modern-normalize](https://github.com/sindresorhus/modern-normalize)

## 🚀 Features

1. ✨ Consistent: Ensures uniform styles across various browsers.  
1.1 Apply `box-sizing: border-box;`, resets padding, and margin.  
1.2 Improve font consistency.  
1.3 Form styles standardization.  
3. 🍃 Lightweight: `modress.min.css` is only 1kb gzipped.
4. 🧩 Fully modular: Take what you want.
5. 🌎 No bundler required: Usable via CDN.

## 📦 Install

```sh
npm install modress
```

## 🦄 Usage

```css
/* app.css */
@import 'modress';
```

or via CDN:

```html
<link rel="stylesheet" href="https://unpkg.com/modress">
```

For usage with Web Components, import individual styles:

```css
/* my-button.css */
@import 'modress/dist/base.css';
@import 'modress/dist/button.css';
```

or:

```html
<link rel="stylesheet" href="https://unpkg.com/modress/dist/base.css">
<link rel="stylesheet" href="https://unpkg.com/modress/dist/button.css">
```

## 🌐 Browser support

- Chrome
- Edge
- Firefox ESR+
- Internet Explorer 10+
- Safari 8+
- Opera

