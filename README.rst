*SDST* catalogue: results for the Survey for Distant Solar Twins
================================================================
The catalogue accompanying the results paper Lehmann et al. (2022b), concluding the Survey for Distant Solar Twins. It contains all relevant information we have extracted during our analysis.

Parameters
----------
The catalogue contains the following parameters:

  Gaia_eDR3_ID : The ID as can be found in Gaia's early data release 3 (Gaia Collaboration et al. 2021)
  
  teff : The effective temperature measured by the EPIC algorithm (Lehmann et al. 2022a)
  
  err_teff : The uncertainty of teff
  
  logg : The surface gravity measured by the EPIC algorithm
  
  err_logg : The uncertainty of logg
  
  feh :  The metallicity measured by the EPIC algorithm
  
  err_feh : The uncertainty of feh
  
  SNR_X : The signal-to-noise ratio in the X band (B, G, R and IR) measured as described in Liu et al. (2022) and Lehmann et al. (2022b)
  
  A_Li : The lithium abundance measured as described in Lehmann et al. (2022b)
  
  err_A_Li : The uncertainty of A_Li
  
  Li_EW_significance : The sigma significance with which the lithium line at 6707A was detected
  
  br_ref : The broadening of the reference spectrum measured as described in Lehmann et al. (2022b)
  
  err_br_ref : The uncertainty of br_ref
  
  br_tar : The broadening of the target spectrum measured as described in Lehmann et al. (2022b)

  err_br_tar : The uncertainty of br_tar
  
  RV : The overall most likely radial velocity measurement determined by the EPIC algorithm
  
  RV_flag : A string made of either "F" or "T". "FFFF" indicates that all bands have measured the same radial velocity while a T in any position 
  indicates that one of the bands has measured an unlikely radial velocity (e.g. "FTFF" indicates that the the G band radial velocity differs 
  from the others)
  
  RV_X : The radial velocity of the X band (B, G, R and IR) measured by the EPIC algorithm
  
  Gmag : The G magnitude as measured by Gaia
  
  Vmag : The V magnitude as measured by Gaia
  
  err_Vmag : The uncertainty of Vmag
  
  plx : The parallax as measured by Gaia
  
  err_plx : The uncertainty of plx
  
  r_med_geo : The median distance derived from plx
  
  r_lo_geo : The lower estimate of the distance derived from plx
  
  r_hi_geo : The upper estimate of the distance derived from plx
  
  r_med_photogeo : The median distance derived from plx and the photometric magnitudes
  
  r_lo_photogeo : The lower estimate of the distance derived from plx and the photometric magnitudes
  
  r_hi_photogeo : The upper estimate of the distance derived from plx and the photometric magnitudes
  
  MedianFlux : The median measured flux with HERMES
  
  MedianSigma : The median sigma uncertainty for measurements with HERMES
  
  teff_nc : The effective temperature measured by the EPIC algorithm using the initial (non corrected) photometric calibration
  
  err_teff_nc : The uncertainty of teff_nc
  
  logg_nc : The surface gravity measured by the EPIC algorithm using the initial (non corrected) photometric calibration
  
  err_logg_nc : The uncertainty of logg_nc
  
  feh_nc :  The metallicity measured by the EPIC algorithm using the initial (non corrected) photometric calibration
  
  err_feh_nc : The uncertainty of feh_nc
  
  age_x, mass_x. logl_x, mv_x, r_x : Measured values of the q^2 algorithm (Ramirez et al. 2014, https://github.com/astroChasqui/q2)
  
  P_ST : The likelihood of a star to be a solar twin according to the solar twin definition in Berke et al. (2022b) and stellar parameters calculated by 
  EPIC
  
  P_SA : The likelihood of a star to be a solar analogue according to the solar twin definition in Berke et al. (2022b) and stellar parameters calculated 
  by EPIC
  
  P_ST_nc : The likelihood of a star to be a solar twin according to the solar twin definition in Berke et al. (2022b) and stellar parameters calculated by 
  EPIC using the initial (non corrected) photometric calibration
  
  P_SA_nc : The likelihood of a star to be a solar analogue according to the solar twin definition in Berke et al. (2022b) and stellar parameters 
  calculated by EPIC using the initial (non corrected) photometric calibration
