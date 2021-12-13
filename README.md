# preview-dvisvgm
Generate SVG images for `preview-latex`

## Installation:
This package requires the [preview-latex package](https://www.gnu.org/software/auctex/manual/preview-latex.html).
It is tested with version 13.0.12 of the preview-latex package.
Furthermore, it requires a working LaTeX installation and the programm [`dvisvgm`](https://dvisvgm.de/).

Put `preview-dvisvgm.el` somewhere in your `load-path` and require it
your init file (e.g., "~/.emacs.d/init.el") with

```lang-el
(require 'preview-dvisvgm)
```

Note, that this package adds an entry for `dvisvgm` to `preview-image-creators`.
(Currently, this appears to be a customization which it isn't. This is a known dept.)

## Usage:
If you like preview-latex to generate svg images customize option `preview-image-type` to "dvisvgm".
