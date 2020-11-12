# clusters_analysis_with_MCMC



king.ipynb

 - uses data file of cluster members, e.g. to_0343_NGC_1502m
 
 - performs MCMC search for the optimal values of 6 parameters: King k, r_c, r_t; cluster centre RA_0, Dec_0; limiting k magnitude
 
 - uses kinematic and photometric filters following prescriptions by A.E. Piskunov and N.V. Kharchenko
 
 - fixed background
 
 
 king_f.ipynb

 - uses data file of cluster members, e.g. to_0343_NGC_1502m
 
 - performs MCMC search for the optimal values of 8 parameters: King k, r_c, r_t; cluster centre RA_0, Dec_0; limiting k magnitude; background; tidal tail contribution
 
 - no kinematic and photometric filters, just star number excess over the background
 
 - contains preliminary estimators of the parameters based on King n- and f-distributions, and log derivative of King n-distribution 
