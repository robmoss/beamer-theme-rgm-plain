## A plain presentation theme for Beamer

This package provides the "rgm-plain" presentation theme for Beamer.
It uses the freely-available
[Open Sans](http://www.google.com/fonts/specimen/Open+Sans) font and the
[Solarized](http://ethanschoonover.com/solarized) colour palette (light mode).

## License

This work is made available under the BSD 2-Clause license (see `LICENSE`).

## Usage

    \usetheme{rgm-plain}

### Options

* `bars`: Show section names and dots for each slide in the frame header;
  this requires the presentation to define sections *and* subsections.
* `dark`: Use the Solarized colour palette (dark mode).
* `emph`: Increase the contrast of the text.
* `heavy`: Use the regular-weight typeface ("Open Sans") in lieu of the
  lighter, default typeface ("Open Sans Light").
* `lining`: Use the Lining number style rather than the default (OldStyle).

### Commands

See `beamerthemergm-plain.sty` for detailed documentation for each of the
following commands:

* `\boldword`: Alternate between displaying a word in plain and bold fonts,
  reserving space for the increased width of the bold text, so that the width
  of the word remains constant.
* `\imageframe`: Create a full-screen image frame.
* `\overeq`: Highlight portions of equations with coloured boxes and coloured
  text above each box; these highlights can be nested.
* `\underereq`: Highlight portions of equations with coloured boxes and
  coloured text below each box; these highlights can be nested.

Also see `example-eqns/example-eqns.tex` for an example of using both
`\overeq` and `\undereq` to describe a set of equations.
