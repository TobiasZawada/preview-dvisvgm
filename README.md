[![MELPA](https://melpa.org/packages/preview-dvisvgm-badge.svg)](https://melpa.org/#/preview-dvisvgm)

# preview-dvisvgm
Generate SVG images for `preview-latex`

## Installation:
This package requires the [preview-latex package](https://www.gnu.org/software/auctex/manual/preview-latex.html).
It is tested with version 13.0.12 of the preview-latex package.
Furthermore, it requires a working LaTeX installation and the programm [`dvisvgm`](https://dvisvgm.de/).

`preview-dvisvgm` is available via [Melpa](https://melpa.org/#/preview-dvisvgm). After setting-up melpa as installation source you can install it with:

<kbd>M-x</kbd> `package-install` <kbd>RET</kbd> `preview-dvisvgm` <kbd>RET</kbd>

Alternatively, put `preview-dvisvgm.el` somewhere in your `load-path` and require it in
your init file (e.g., "~/.emacs.d/init.el") with:

```lang-el
(require 'preview-dvisvgm)
```

Note, that this package adds an entry for `dvisvgm` to `preview-image-creators`.

## Usage:
If you like preview-latex to generate svg images customize option `preview-image-type` to "dvisvgm".
