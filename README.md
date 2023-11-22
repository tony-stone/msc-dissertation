# Bookdown disseration template: instructions

* Put your name and dissertation title in frontpage.tex

* Put your acknowledgements and lay summary in index.Rmd

* Create one .Rmd file per chapter, with the chapter number at the start of the file name
   - these chapter files do not include any YAML at the start
   - make the first line of each file, start with # Chapter name

* To build the various files into a pdf document in Rstudio
   - open the R project in the root folder of this zip archive and then use Build Book > bookdown::pdf_document2;
   - the pdf and tex files will appear in the _book folder;
   - generated plots will go in the _bookdown_files/dissertation_files/figure-latex folder.

* For a guide to using bookdown, see https://bookdown.org/yihui/bookdown/
   - this template is set up for producing a pdf using the LaTeX dissertation template; some features may not work if trying to knit to other formats (e.g. a gitbook).
