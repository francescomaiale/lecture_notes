# Lecture Notes

A collection of LaTeX lecture notes on computational fluid dynamics, numerical methods, and applied mathematics.

## Contents

| Course | Topics | PDF |
|--------|--------|-----|
| [Group Theory](./group_theory/) | Group theory in Physics | [PDF](./group-theory/main.pdf) |
| [Advanced Analysis](./aa/) | Advanced analysis, Fourier transform, etc. | [PDF](./aa/pdf/main.pdf) |
| [Analysis of Sublaplacian operators](./analysis_sublaplacian/) | Sublaplacian on Lie groups | [PDF](./analysis_sublaplacian/pdf/main.pdf) |
| [Calculus of variations](./calculus_variations/) | Calculus of variations, direct and indirect methods | [PDF](./calculus_variations/pdf/main.pdf) |

<!-- Add more courses as needed -->

## Repository Structure

```
lecture-notes/
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

Francesco Paolo Maiale — [francescopaolo.maiale@gssi.it](mailto:francescopaolo.maiale@gssi.it)

## Acknowledgments

<!-- Optional: acknowledge collaborators, institutions, funding, etc. -->
