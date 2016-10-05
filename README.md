R for Reproducible Scientific Analysis 
======================================

Modifications of Software Carpentry [r-novice-gapminder](https://github.com/swcarpentry/r-novice-gapminder) for a pilot Data Carpentry [workshop for Social Scientists](michaellevy.name/2016-06-16-ucdavis/)

### Introduction to R for non-programmers using gapminder data

The goal of this lesson is to introduce novice programmers to R tools and syntax, as well as best practices in data management and analysis. The emphasis of these materials is to give attendees a strong motivation to continue learning R, to introduce some common, powerful packages for data manipulation and analysis, and to teach best practices for scientific computing.

Note that this workshop focuses on teaching the fundamentals of the programming language R, and while it introduces statistical functions, does not teach statistical analysis.

A variety of third party packages are used throughout this workshop. These are not necessarily the best, nor are they comprehensive, but they are packages we find useful, and have been chosen primarily for their usability.

These lesson materials are adapted from the [R-novice-inflammation](http://swcarpentry.github.io/r-novice-inflammation) materials, which were translated from the Python materials, and materials from our [R Data Carpentry materials used at the Sydney bootcamp last year](https://dbarneche.github.io/2014-10-31-USyd/). 

## Contributing

Please see the current list of [issues][] for ideas for contributing to this repository, and the [guidelines and instructions for contributing][contrib].

When editing topic pages, you should change the source R Markdown file. Afterwards you can render the pages by running `make preview` from the base of the repository. Building the rendered page with the Makefile requires installing some dependencies first. In addition to the dependencies listed in the [lesson template documentation][dependencies], you also need to install the R package [knitr][].

Once you've made your edits and looked over the rendered html files, you should add, commit, and push the fully compiled site.

## Getting Help

Please see [https://github.com/swcarpentry/lesson-example](https://github.com/swcarpentry/lesson-example) for instructions on formatting, building, and submitting lessons, or run `make` in this directory for a list of helpful commands.

If you have questions or proposals, please send them to the [r-discuss][] mailing list.

[contrib]: https://github.com/swcarpentry/r-novice-gapminder/blob/gh-pages/CONTRIBUTING.md
[dependencies]: https://github.com/swcarpentry/lesson-template#dependencies 
[design]: https://github.com/swcarpentry/lesson-template/blob/gh-pages/DESIGN.md
[issues]: https://github.com/swcarpentry/r-novice-gapminder/issues 
[knitr]: http://cran.r-project.org/web/packages/knitr/index.html 
[r-discuss]: http://lists.software-carpentry.org/mailman/listinfo/r-discuss_lists.software-carpentry.org