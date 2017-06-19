Simple Models are the ones that work best.  grbm, sbpl


grbm+lpow:  PL is insignificant and not at a good angle.  NO ERRORS

sbpl+lpow:  Same as grbm+lpow.  NO ERRORS

grbm+blackb:  BBODY not very important.  NO ERRORS.  Getting this warning: ***Warning: Parameter pegged at hard limit: 0.1
	***Warning: Parameter pegged at hard limit: 1e-10
	***Warning: New best fit found, fit parameters will be set to new values.
	not sure why because none of the norm parameters are at the edge.

sbpl+blacb:  I changed the hard limits on the norm parameters back to 10^-15 because the errors were complaining.  I only got 1-sigma errors and there were complaints.  Once again, the BBODY isn't very significant.

copl+lpow:  Errors and looks good, but didn't give the best AIC and BIC.

grbm+blackb+lpow:  Not a realistic setup.