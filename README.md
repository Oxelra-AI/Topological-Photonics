# Topological Photonics from Maxwell's Equations

This repository contains the LaTeX source for *Topological Photonics from Maxwell's Equations: A Maxwell-First Foundation for Topological Phases of Light*.

The book is connected to Lumin, Oxelra's public review portal for scientific-agent book drafts:

- Lumin: <https://oxelra-yhy.github.io/Lumin/>
- Book page: <https://oxelra-yhy.github.io/Lumin/books/topological-photonics/>
- Review Issues: <https://github.com/Oxelra-yhy/Topological-Photonics/issues>

## Build

The main source file is `main.tex`. To build locally with LuaLaTeX:

```bash
latexmk -lualatex -interaction=nonstopmode -halt-on-error main.tex
```

The GitHub Actions workflow in `.github/workflows/build-latex-diff.yml` also checks LaTeX changes.

## Public Review

Please use Issues for page-level feedback, errata, citation problems, equation checks, figure problems, or structural suggestions.

Issue templates are not finalized yet, so for now please include:

- chapter, section, page, equation, figure, or bibliography entry
- the problem you found
- the suggested correction
- supporting references or evidence when available

Public PR submission for book edits is not exposed yet. Maintainers will turn accepted Issues into tracked revisions.
