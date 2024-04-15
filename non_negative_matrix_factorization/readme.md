# Non-negative matrix factorixation
The iPython notebook (`.ipynb` file) can be used to conduct non-negative matrix  
factorization analysis for a series of data files.

The data are expected to contain $x$-values in the first column and the  
$y$-values in the second column. Header as well as additional columns can be  
handled.

The data files should be named with a frame number prepended to the filename,  
e.g. `00_filename.ext`.

The reconstruction error as a function of the number of components should be  
used as guidance for the number of components needed to describe the trends in  
the data.

The nmf analysis will be conducted for a series of components, plotting:
- the normalized weights as a function of the frame number.
- the nmf components.

Doing the analysis for a range of components allows for an iterative analysis  
procedure, enabl
