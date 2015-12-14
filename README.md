# Bright theme for Shower

A theme for the [Shower](https://github.com/shower/shower/) presentation engine. Doesn’t include engine itself. Follow [@shower_me](https://twitter.com/shower_me) for support and updates, [file an issue](https://github.com/shower/shower/issues/new) if you have any.

**Attention!** Staring from Shower 2.0 it’s no longer supported or included by default in [template](https://github.com/shower/shower/), though it’s fully compatible. Please consider moving to [Material](https://github.com/shower/material/) theme which is visually similar.

## Usage

Install the package and link styles from your presentation:

	npm install shower-bright

The same package available in [bower](http://bower.io/).

## Features

All theme’s features are demonstrated in the `index.html` file. Use it as a reference while building your presentation.

## Ratios

Bright theme supports two slide ratios: wide 16×10 (default) and taller 4×3. To change the slide’s ratio change `$ratio` variable in [`defaults.scss`](styles/defaults.scss) file from `16x10` to `4x3` and rebuild styles.

## PDF

Bright could be exported to PDF by printing it from the list mode in Chrome or Opera browsers.

## Development

If you want to adjust theme for your needs:

1. Fork this repository and clone it to your local machine.
2. Install dependencies: `npm install`.
3. Build styles with `grunt`, start a watcher for styles with `grunt watch`.
4. Edit your files and see changes in `index.html`.

To take part in Bright development please read [contributing guidelines](CONTRIBUTING.md) first and [file an issue](https://github.com/shower/shower/issues/new) before sending any pull request.

---
Licensed under [MIT License](LICENSE.md).
