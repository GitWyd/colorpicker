# PyBullet Color Picker

A lightweight, single-page web tool that lets you pick any color and instantly retrieve the corresponding PyBullet RGBA array.

---

## Demo

Try it out live on GitHub Pages:  
[https://GitWyd.github.io/colorpicker/](https://GitWyd.github.io/colorpicker/)

---

## Features

- 🎨 **Real‑time RGBA Conversion**: Pick a color and alpha value; the tool automatically computes `[r, g, b, a]` floats in the range [0, 1].
- 📋 **One‑click Copy**: Copy the RGBA string to your clipboard with a single click.
- 🌗 **Dark & Light Modes**: Automatically matches your system theme via `prefers-color-scheme`.
- 📱 **Responsive UI**: Mobile‑style card layout that scales smoothly across screen sizes.
- 🖥️ **Single File**: Contains all HTML, CSS, and JavaScript in one `index.html`—no dependencies.

---

## Usage

1. Clone or download this repository.
3. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).
4. Choose your desired color and opacity.  
5. Click **Copy RGBA** to grab the `[r, g, b, a]` string for PyBullet.

---

## Installation

No installation required. Just host the single `index.html` on any static server or GitHub Pages.

---

## Development

If you’d like to customize or contribute:

1. Fork this repo and create a feature branch (`git checkout -b feature/foo`).
2. Commit your changes (`git commit -am 'Add some foo'`).
3. Push to the branch (`git push origin feature/foo`).
4. Open a Pull Request.

---

## License

This project is released under the CC0 1.0 Universal License. See [LICENSE](LICENSE) for details.
