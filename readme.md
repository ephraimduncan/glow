# Glow

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![glow-css on NPM](https://img.shields.io/npm/v/glow-css.svg?color=green&label=glow-css)](https://www.npmjs.com/package/glow-css)

A small CSS utility to make glow text and images.

## Installation

### CSS quick start (easy)

- Use the CDN URL: https://unpkg.com/glow-css@0.2.0/dist/css/glow.min.css.

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/glow-css@0.2.0/dist/css/glow.min.css"
/>
```

It's all set to go and your HTML elements will be given sensible default styling.

## Styling

### Colors

primary: `#0050fd`<br>
secondary: `#a5a2a2`<br>
success: `#00ff0d`<br>
danger: `#ff2600` <br>
warning: `#fdec00`<br>
info: `#5aa2ff`<br>
light: `#ffffff`<br>
dark: `#282828`<br>

### Text

Add `glow-{color}` to glow the text with the specified colors

```html
<p class="glow-primary">
  Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, vel.
</p>
```

### Images

Add `glow-img-{color}` to glow the image.
_Recommended for images with transparent background_

```html
<img alt="mario" class="glow-img-dark" src="./mario.png" />
```

## Contributing

Please feel free to fork, comment, critique, or submit a pull request.

## License

This project is open source and available under the [MIT License](LICENSE.md).
