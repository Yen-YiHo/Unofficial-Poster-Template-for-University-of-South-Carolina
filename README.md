# Unofficial Poster Template for University of South Carolina
 [![Overleaf Template](https://img.shields.io/badge/Overleaf-Template-success?logo=overleaf)]

A fork of Gemini and can be easily imported to Overleaf. 

![gemini_UofSC](https://people.stat.sc.edu/hoyen/Unofficial_Poster_Template_for_University_of_South_Carolina.jpg)

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

## FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how
to add an institution logo to the poster.

