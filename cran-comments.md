## This is the fifth resubmission

* Actions taken since previous resubmission:
  * Added arguments 'save_gate', 'name_gate', and 'path_gate' in lotrrs(), rrs(), and gating() to save plots as PNG files as output
  * Renamed 'doplot' argument as 'plot_gate' for consistency with new plotting arguments
  * Added a stop (and return no results) if no significant clusters detected during first gate
  * Removed 'verbose' argument in gating(), rrs(), and lotrrs()
  * Added try() error catches in rrs() and lotrrs() for 'c1n' and 'c2n' arguments
  * Changed the 'right' argument in cut() in pval_plot() to "TRUE" (the default)
  * Removed fullstop in error messages
  * Added a make.names() check for vars and colnames(dat) in gating()
  
## Test environments
* local OS X install, R 3.6.3
* win-builder, (devel, oldrelease, release)
* Rhub
  * Fedora Linux, R-devel, clang, gfortran
  * Ubuntu Linux 16.04 LTS, R-release, GCC
  * Windows Server 2008 R2 SP1, R-devel, 32⁄64 bit

## R CMD check results
0 errors | 0 warnings | 0 notes

## Submitted by Maintainer
