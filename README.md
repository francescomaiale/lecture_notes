# Lecture Notes

A collection of LaTeX lecture notes on computational fluid dynamics, numerical methods, and applied mathematics.

## Contents

| Course | Topics | PDF |
|--------|--------|-----|
| [Numerical Methods](./numerical-methods/) | Finite differences, shooting method, iterative solvers | [PDF](./numerical-methods/main.pdf) |
| [Computational Fluid Dynamics](./cfd/) | Immersed boundary methods, SDF computations | [PDF](./cfd/main.pdf) |

<!-- Add more courses as needed -->

## Repository Structure

```
lecture-notes/
├── common/                 # Shared resources
│   ├── preamble.tex        # Common packages and macros
│   └── bibliography.bib    # Shared references
├── course-name/
│   ├── main.tex            # Main document
│   ├── chapters/           # Chapter files
│   ├── figures/            # Images and diagrams
│   └── main.pdf            # Compiled output
```

## Compilation

Each course can be compiled independently. Navigate to the course folder and run:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Or using `latexmk` (recommended):

```bash
latexmk -pdf main.tex
```

To clean auxiliary files:

```bash
latexmk -c
```

## Requirements

- A LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Standard packages: `amsmath`, `amssymb`, `amsthm`, `graphicx`, `hyperref`

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this material, provided you give appropriate credit.

## Author

Francesco — [your.email@example.com](mailto:your.email@example.com)

## Acknowledgments

<!-- Optional: acknowledge collaborators, institutions, funding, etc. -->
