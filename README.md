# @denali-design/icons

:construction: (WIP)

## What is Denali Icons?

Denali Icons library consisting of 1000+ unified icons packaged into a font, SVG, sprite, and JS library.

https://denali.design

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Font](#font)
  - [SVG](#svg)
  - [SVG Sprite](#svg-sprite)
- [Contributing](#contributing)
- [License](#license)

---

## Installation

### NPM

Install via [NPM](https://www.npmjs.com/)

```
npm install @denali-design/icons
```

### CDN

Install via [jsdelivr](https://www.jsdelivr.com/)

Refer to the usage section for specific examples.

---

## Usage

### Font

Link to the CSS font file in the head of your page or app:

```html
<link rel="stylesheet" href="path/to/denali-icons-font.css">
```
or CDN
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/denali-icons/dist/denali-icons-font.css">
```

Include an icon in your app or page with the following markup:

```html
<span class="d-icon d-pencil"></span>
```

---

### SVG

Just your basic svg files.

Include with the svg markup from each icon in your app:

```html
<svg
  class="d-icon"
  xmlns="http://www.w3.org/2000/svg"
  width="48"
  height="48"
  viewBox="0 0 48 48"
>
  <title>accessibility</title>
  <g id="Layer_2" data-name="Layer 2">
    <g id="invisible_box" data-name="invisible box">
      <rect width="48" height="48" fill="none" />
    </g>
    <g id="Layer_6" data-name="Layer 6">
      <g>
        <circle cx="24" cy="7" r="4" />
        <path
          d="M40,13H8a2,2,0,0,0,0,4H19.9V27L15.1,42.4a2,2,0,0,0,1.3,2.5H17a2,2,0,0,0,1.9-1.4L23.8,28h.4l4.9,15.6A2,2,0,0,0,31,45h.6a2,2,0,0,0,1.3-2.5L28.1,27V17H40a2,2,0,0,0,0-4Z"
        />
      </g>
    </g>
  </g>
</svg>
```

or link to the icon through your preferred installation method.

```html
<img class="d-icon" src="/path/to/accessibility.svg" />
```
or CDN
```html
<img class="d-icon" src="https://cdn.jsdelivr.net/npm/denali-icons/dist/svg/accessibility.svg" />
```

---

### SVG Sprite

A SVG sprite is an svg file that contains multiple images. This allows you to include one file, but use many images. Perfect for icon libraries.

> **NOTE:** An alternative installation method is to copy [denali-icons-sprite.svg]() into your project.

Include an icon in your app or page with the following markup:

```html
<svg class="d-icon">
  <use xlink:href="path/to/denali-icons-sprite.svg#denali"></use>
</svg>
```
or CDN
```html
<svg class="d-icon">
  <use xlink:href="https://cdn.jsdelivr.net/npm/denali-icons/dist/denali-icons-sprite.svg#denali"></use>
</svg>
```

---

## Contributing

See the [Contributing](CONTRIBUTING.md) guide for details.

---

## License

This project is licensed under the [MIT License](LICENSE.md).
