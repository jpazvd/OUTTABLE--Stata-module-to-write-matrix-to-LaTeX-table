# OUTTABLE: Stata module to write matrix to LaTeX table

## Description

outtable automates the conversion of a Stata matrix to a LaTeX table, written to an external file.
The table is presented with row and column names taken from the specified matrix.  Thus, one need
only generate the appropriate matrix using standard Stata commands. By default, only the lower
triangle of a symmetric matrix will be written, as inferred by Stata's issym() function.

The using clause is required, and must specify the name of a file to which the LaTeX table is to be
written, without the .tex extension. If the file exists, either the replace option or the append
option must be specified.

The mat qualifier specifies the name of the existing matrix which is to be written in tabular form.

## Suggested Citation
[Christopher F Baum & Joao Pedro Azevedo, 2001. "OUTTABLE: Stata module to write matrix to LaTeX table," Statistical Software Components S419501, Boston College Department of Economics, revised 03 Aug 2014.](https://ideas.repec.org/c/boc/bocode/s419501.html)

### Handle: RePEc:boc:bocode:s419501 

### Note: 
This module may be installed from within Stata by typing "ssc install outtable". Windows users should not attempt to download these files with a web browser.

### Keywords
data handling; LaTeX; matrices


## Authors: 

  **Christopher F Baum**  

  **João Pedro Azevedo**  
  [jazevedo@worldbank.org](mailto:jazevedo@worldbank.org)  
  World Bank  
  [personal page](http://www.worldbank.org/en/about/people/j/joao-pedro-azevedo)  

