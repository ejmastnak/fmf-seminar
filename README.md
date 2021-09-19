
# Seminar
Source files for Elijan Mastnak's paper and presentation for the Seminar course requirements at the Faculty of Math and Physics at the University of Ljubljana. The project explores the use of convolutional neural networks for classifying the products of high-energy collisions in particle physics. See [About the Seminar course at FMF](#about-the-seminar-course-at-fmf) below for context.

### Project structure
- `bib` holds the project's `biblatex` bibliography database
- `media` holds the diagrams, images, and animations used in the paper and presentation
- `presentation-slo` holds a Slovene version of the presentation's LaTeX source files
- `presentation` is the English analog of `presentation`
- `report` holds paper's LaTeX source files (in English)
- `svg-figure-files` holds the `svg` files used to make the paper and presentation's diagrams

### Software used to make the project
- The paper and presentations are written in LaTeX using the `article` and `beamer` classes, respectively
- The bibliography files are managed using the `biblatex` package with the `biber` backend; the paper's bibliography uses the `atlasbiblatex` style.
- The project's `tex` files were compiled with [John Collins' `latexmk` script](https://ctan.org/pkg/latexmk/). Regular `pdflatex` also works but can give unexpected results with bibliography references.

- Figures were created with the `Inkscape` vector graphics application; I used the `TexText` extension to incorporate LaTeX code into the figures. All files in `svg-figure-files` are saved in Inkscape's `Inkscape SVG` format.


### About the Seminar course at FMF
*Seminar* is a required course for students in the final semester of the undergraduate physics program at the Faculty of Mathematics and Physics at the University of Ljubljana. In the scope of the course, students, under the guidance of a faculty mentor, write an undergraduate thesis on a currently relevant physics topic and present the topic to their classmates.

The project encompasses two parts:
- a written paper (no more than about 20 pages)
- a roughly 35 to 40-minute slide-show presentation to the student's classmates, course coordinator, and mentor, followed by questions from the audience and a seminar-style discussion of the topic.

The Seminar is intended primarily as an exercise in clear scientific writing and presentation, a training of sorts for giving presentations at scientific conferences. However, students are not expected (nor encouraged) to produce original research in the scope of the Seminar, simply to clearly present their chosen topic at a level suitable (i.e. not too advanced) for a general final-year undergraduate audience.
