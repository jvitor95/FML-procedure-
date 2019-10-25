
# FML-procedure-
A simple Rstudio function for enabling the testing of dispersion effects in factorial designs.

;;; PROCEDURE:

;;;   FML Function

;;; PARAMETERS:

;;;   vars, a vector containing the variances of the response

;;;   xmat, a matrix consisting of +/-1 which indicates the level of a factor

;;;   replications, the number associated with the calculation of vars

;;; PURPOSE:

;;;   Tests for dispersion effects in a factorial design

;;; PRODUCES:

;;;;  pvalvec, a vector of pvalues

;;; PRECONDITIONS:

;;;   replications must be greater than 1.

;;;    length(vars) == nrow(xmat)

;;;    length(vars) must be a power of 2
