My first try to generate translator's intergloss helper files.

The file `bible.tex` includes the lexicon definitions `lexicon.tex` (to be continuously changed), the definitions of the books' names `booknames.tex` and the actual content of every verse `words.tex`.

To be compiled with `xelatex bible.tex`. Example of an output in `bible.pdf`. As of June 8, 2020, the compilation takes 6 mins and produces a `pdf` file of 43 Mb with 7163 pages.

The files `words.tex`, `lexicon.tex`, `booknames.tex` are generated in the bosom of the notebook `GenerateLatexTemplate.ipynb`. It uses the data from the project [https://wlcling.github.io](https://wlcling.github.io) (see the `_data` folder).

This project is inactive since June 8, 2020. I found it faster and more useful to generage those helper files in `html` (see [https://bh.seveleu.com/](https://bh.seveleu.com/), section "Gloss translations"). For this reason, I leave the notebook `GenerateLatexTemplate.ipynb` in its actual state (beware!).
