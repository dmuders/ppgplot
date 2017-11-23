## ppgplot
Wrappers for using pgplot in python 2 and 3.

# History

The original ppgplot implementation is by Nick Patavalis (https://github.com/npat-efault/ppgplot). This version is a slightly modified version that part of PRESTO (https://github.com/scottransom/presto) by Scott Ransom, for which Matteo Bachetti provided python 3 support.

# Installation

First install *pgplot* (http://www.astro.caltech.edu/~tjp/pgplot/) using `gfortran` as the Fortran compiler. Then set the PGPLOT_DIR environment variable. Once *pgplot* is installed, install *ppgplot* with

    python setup.py install

Test the *ppgplot* installation by running `import ppgplot` and `ppgplot.pgopen("/xs")` in python.
