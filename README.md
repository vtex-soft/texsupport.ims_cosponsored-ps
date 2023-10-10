# PS

## DESCRIPTION

LaTeX author support files for IMS co-sponsored journal: 
[Probability Surveys (PS)](https://imstat.org/journals-and-publications/probability-surveys/)

## FILE LIST

-   `ps-sample.tex` - sample article for PS (source file)
-   `ps-sample.pdf` - sample article for PS (PDF compiled)
-   `figure1.eps`, `figure1.pdf` - sample figures for `ps-sample.pdf`
-   `LICENSE` - a copy of the LaTeX Project Public License
-   `README.md` - this file itself!
-   `imsart.cls`, `imsart.sty` - LaTeX style files
-   `acmtrans-ims.bst`, `imsart-nameyear.bst`, `imsart-number.bst` - BibTeX style files

## INSTRUCTIONS FOR PS AUTHORS

-   You only need `imsart.cls`, `imsart.sty`, `ps-sample.tex`, and `ps-sample.pdf`
-   Take the time to read `ps-sample.pdf`
-   Copy `ps-sample.tex` into `yourname.tex`
-   Edit `yourname.tex` (update metadata and the content of the paper)
-   Use `acmtrans-ims.bst`, `imsart-nameyear.bst`, `imsart-number.bst` BibTeX styles to prepare bibliography file. 
    More information can be found [here](http://www.bibtex.org/Using/) 
    or [here](https://www.latex-tutorial.com/tutorials/bibtex/).
-   Be sure to have `imsart.cls`, `imsart.sty` in the same directory (or any dir scanned for `cls`)
-   Compile `yourname.tex` to generate `yourname.pdf` with a `pdflatex` or `lualatex` program and check the result
-   More detailed instructions for authors are available on Internet: https://imstat.org/journals-and-publications/probability-surveys/

## TROUBLESHOOTING

-   To remove frame from the text box use document class option `noshowframe`, e.g:

        \documentclass[ps,noshowframe]{imsart}

## BUG REPORTS

Please submit bug reports and/or feature requests
at [GitHub page](https://github.com/vtex-soft/texsupport.ims_cosponsored-ps/issues) or 
[latex-support@vtex.lt](mailto:latex-support@vtex.lt).
