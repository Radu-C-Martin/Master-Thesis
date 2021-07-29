# Inter-seasonal GP MPC control for buildings

## Report and Presentation slides

This repository contains the code for the report and presentation slides for my
Master Project 
> *Inter-seasonal Performance of Gaussian Process-based 
> Model Predictive Control of Buildings*

which was done under the supervision of Prof. Colin Jones at the EPFL's
[Automatic Control Laboratory](https://www.epfl.ch/labs/la/)

The main folder structure is as follows: 

```shell
└── Thesis
    ├── Images
    ├── Plots
    └── Sections
```

The `Images` and `Plots` folders contain the figures used in the thesis and are
shared between the report and the presentation. The `Sections` folder contains
the content of documents. 

In order to compile the documents, the appropriate main file has to be chosen: 

- `thesis.tex` compiles the project report
- `slides_clean.tex` compiles the presentation slides, not including the notes
- `slides_notes.tex` compiles the presentation slides, including the notes on
  the right side of the screen.

The resulting presentation pdf contains an embedded video file. It can be played
back using a compatible pdf reader, such as okular or pympress.

---

The presentation is based on the
[beamer template](https://www.overleaf.com/latex/templates/eesd-presentation-latex-template/sfqmhmqxhmjy)
by Mahmoud Shaqfa.
