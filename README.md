# LaTeX packages

These packages can be placed under `$HOME/texmf/tex/latex/local/`.
You can find the appropriate location with `kpsewhich -var-value=TEXMFHOME`,
as discussed [here](http://tex.stackexchange.com/a/1138/8666).
You may need to run `texhash $HOME/texmf` after placing the files.

- `svglatex.sty`: package for interfacing with inkscape, to be used with [this](
    https://github.com/johnyf/svglatex).
- `mycommands.sty`: Several commands for including multiple graphics, and
  for formatting mathematics.
- `tlamath.sty`: a small excerpt from and wrapper of the TLA+ LaTeX styles
- other custom LaTeX convenience commands, mainly in:
  - `mycommands.sty`
  - `mytheorems.sty`
  - `my_theorem_styles.sty`
  - `ieeeconf_custom.sty`
  - `formal_methods_commands.sty`
- preambles I use for `XeLaTeX` documents and `beamer`
- Caltech beamer theme (courtesy [Scott Livingston](https://github.com/slivingston/misc/tree/master/presentation_templates))
- Greek hyphenation

Licensed under BSD-2, except for `beamerthemePasadena.sty` that is under GPL.
