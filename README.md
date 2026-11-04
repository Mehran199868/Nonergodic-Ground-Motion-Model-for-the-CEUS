###########################################################################################
Nonergodic Ground Motion Model for the Central and Eastern United States (CEUS)
###########################################################################################
######################
Overview
######################
This repository accompanies the study by Mehran Davatgari-Tafreshi, Shahram Pezeshk, and 
Kenneth Campbell (????) on a nonergodic ground motion model (NGMM) for the Central and 
Eastern United States (CEUS). It includes the study dataset and the results of the nonergodic 
site and source adjustments developed by the authors.
######################
Folder Structure
######################
a.The nonergodic adjustment terms
  1-dc_0_mean: Constant offset of the nonergodic GMM relative to the ergodic backbone model
  2-dc_0_sig: Epistemic uncertainties associated with dc_0_mean
  3-dc_1e_mean: Spatially varying source adjustment as a function of earthquake coordinates
  4-dc_1e_sig: Epistemic uncertainties associated with dc_1e_mean
  5-dc_1as_mean: Spatially independent site adjustment indexed by station ID
  6-dc_1as_sig: Epistemic uncertainties associated with dc_1as_mean
  7-dc_1bs_mean: Spatially varying site adjustment as a function of site coordinates
  8-dc_1bs_sig: Epistemic uncertainties associated with dc_1bs_mean

b. Combined_Flatfile
   This file contains the combined dataset used in the analysis.
   It was compiled from three independent datasets: Goulet et al. (2014),
   Chapman and Guo (2021), and Thompson et al. (2023).


######################
   Citation
######################
When using these files, cite the accompanying manuscript, this dataset
using its repository DOI, and the relevant original data sources:
Goulet et al. (2014), Chapman and Guo (2021), and Thompson et al. (2023).

Chapman, M. C., & Guo, Z. (2021).  A response spectral ratio model to account for amplification and attenuation effects in the Atlantic and Gulf Coastal Plain. Bulletin of the Seismological Society of America, 111(4), 1849-1867.

Goulet, C. A., Cramer, C. H., Darragh, R. B., Silva, W. J., Hashash, Y. M. A., Harmon, J., Stewart, J. P., Wooddell, K. E., and Youngs, R. R. (2014).  PEER NGA-East Database.  PEER Rep. /201417, Berkeley, CA: Pacific Earthquake Engineering Research Center.

Thompson, E. M., Boyd, O. S., Churchwell, D., & Moschetti, M. P. (2023).  Central and Eastern US earthquake ground motion database: 2010 to 2020. Center for Engineering Strong Motion Data (CESMD). DOI, 10, P9HX7MYG.
