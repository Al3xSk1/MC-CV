# Minecraft CV / Resume

This repository contains my Minecraft development CV/resume, written in LaTeX.
It focuses on my experience building Minecraft server-side systems, plugins,
custom gameplay mechanics, and related infrastructure.

The main source file is [`CV.tex`](CV.tex).

## Building

If you have a LaTeX toolchain installed, build the resume with:

```sh
latexmk -pdf CV.tex
```

The generated PDF can then be used as the current resume copy.

## PDF Release

GitHub Actions builds the resume whenever `CV.tex` changes on `main` and
publishes a rolling `cv-pdf` prerelease with the finished `CV.pdf` attached.

## License

All rights reserved. See [`LICENSE`](LICENSE) for details.
