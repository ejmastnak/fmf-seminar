# Seminar
Source files for Elijan Mastnak's paper and presentation for the *Seminar* course requirements at the Faculty of Math and Physics at the University of Ljubljana. The project explores the use of convolutional neural networks for classifying the products of high-energy collisions in particle physics; you can read more on [my website](https://ejmastnak.github.io/projects/seminar/seminar.html). 

### Want a PDF?
See [ejmastnak.github.io/projects/seminar/paper.pdf](https://ejmastnak.github.io/projects/seminar/paper.pdf) for an up-to-date, pre-compiled PDF.

### Project structure
- `bib` holds the project's `biblatex` bibliography database
- `media` holds the diagrams, images, and animations used in the paper and presentation
- `presentation-slo` holds a Slovene version of the presentation's LaTeX source files
- `presentation` is the English analog of `presentation-slo`
- `paper` holds the paper's LaTeX source files (in English)
- `svg-figure-files` holds the `svg` files used to make the paper and presentation's diagrams

### Software used to make the project
- The paper and presentations are written in LaTeX using the `article` and `beamer` classes, respectively

- The bibliography files are managed using the `biblatex` package with the `biber` backend; the paper's bibliography uses the `atlasbiblatex` style.

- The project's `tex` files were compiled with [John Collins' `latexmk` script](https://ctan.org/pkg/latexmk/). Regular `pdflatex` also works but can give unexpected results with bibliography references.

- Figures were created with the `Inkscape` vector graphics application; I used the [TexText](https://textext.github.io/textext/) extension to incorporate LaTeX code into the figures. All files in the `svg-figure-files` directory are saved in Inkscape's `Inkscape SVG` format.

- I used the [`pdfpc` presenter console](https://pdfpc.github.io/) to present the slide show.


### About the Seminar course at FMF
*Seminar* is a required course for students in the final semester of the undergraduate physics program at the Faculty of Mathematics and Physics at the University of Ljubljana. In the scope of the course, students, under the guidance of a faculty mentor, write an undergraduate thesis on a currently relevant physics topic and present the topic to their classmates.

The project encompasses two parts:
- a written paper (no more than about 20 pages)
- a 35 to 40-minute slide-show presentation to the student’s classmates, course coordinator, and mentor, followed by questions from the audience and a seminar-style discussion of the topic.

The project is intended primarily as an exercise in clear scientific writing and presentation, a training, in some sense, for giving presentations at scientific conferences. However, undergraduate students are neither expected nor encouraged to produce original research in the scope of the Seminar course, simply to clearly present their chosen topic at a level suitable (i.e. not too advanced) for a general final-year undergraduate audience.

### License
The contents of the directories `paper`, `presentation`, `presentation-slo`, and `svg-figure-files` are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa] 

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
