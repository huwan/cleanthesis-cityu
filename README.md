# cleanthesis-cityu

An XeLaTeX thesis template for research postgraduate (MPhil and PhD) and professional doctorate (PD) students at City University of Hong Kong.

This thesis tempalte builds upon the [Clean Thesis](https://github.com/derric/cleanthesis) from Ricardo Langner. It is adapted to meet the regulations governing the format of theses (as of 2018-19).

Please read Regulations Governing the Format of Theses and Sample of the Front Cover/Spine/Title Page of a Thesis (Appendixes 12 and 13 of the [Guidebook for Research Degree Studies](https://www.sgs.cityu.edu.hk/student/rpg/studentGuideBook)). See [my-thesis.pdf](my-thesis.pdf) for an example PDF created with this template.

Credit goes to Ricardo Langner, author of the Clean Thesis above.

This template is included in **[CityU-Thesis](https://github.com/huwan/CityU-Thesis)**, a collection of LaTeX thesis template for students at City University of Hong Kong. You can find more templates in that repository.


## Prerequisites

- **Fonts**: Times New Roman and MingLiU/細明體 (PMingLiU/新細明體) should be used in the title page of a thesis to provide thesis information in both Chinese and English. Make sure they have already been installed system-wide.

- **XeLaTeX**: Configure your document to be compiled with `XeLaTeX` typesetting engine to use the external fonts above.


## Usage

The main file is `my-thesis.tex`, from which a number of other files are included. Take a look at the comments in the LaTeX sources for some more specific pointers.

To compile, simply run `my-thesis.tex` through `XeLaTeX`.

See Clean Thesis' original [README](README-cleanthesis.md) for more details.

## Online

cleanthesis-cityu is added to the Overleaf Gallery. You can find it [here](https://www.overleaf.com/latex/templates/thesis-teamplate-city-university-of-hong-kong-with-cleanthesis/chjmxtmnqjmp).

## License

[Clean Thesis](https://github.com/derric/cleanthesis) by Ricardo Langner is licensed under the LaTeX Project Public License (version 1.3).
