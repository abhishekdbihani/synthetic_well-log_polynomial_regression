## Constructing a Synthetic NMR Well-log using Machine Learning

### Final Project for PGE 383 – Subsurface Machine Learning by Abhishek Bihani

**Summary:** The nuclear magnetic resonance (NMR) log is a useful tool to understand lithological information such as the variation of pore size distribution with depth, but it may not be measured in all wells. This project attempts to construct a missing well log from other available well logs, more specifically an NMR well log  from the measured Gamma Ray (GR), Caliper, Resistivity logs and the interpreted porosity from a well at the Keathley Canyon in the Gulf of Mexico. 

First, initial analysis is conducted on the well logs, followed by feature ranking. Thereafter, the logs are processed and polynomial regression modeling is conducted. The constructed model is then used to predict the NMR log  at Walker Ridge in Gulf of Mexico, which is another nearby site of methane hydrate accumulation. 

In Keathley Canyon Block 151, the analyzed well was drilled and logged during Leg I of the U.S. Department of Energy/Chevron Gas Hydrate Joint Industry Project (JIP) (Ruppel et al., 2008). At Walker Ridge, the analyzed well was drilled and logged during JIP Leg II (Collett et al., 2012).

The workflow has been adapted from the Dr. Michael Pyrcz's [Subsurface Machine Learning course](https://github.com/GeostatsGuy/SubsurfaceMachineLearning) and my [Master's research thesis](https://www.pge.utexas.edu/images/pdfs/theses16/bihani.pdf)

<img src="https://github.com/abhishekdbihani/synthetic_well-log_polynomial_regression/blob/master/KC151-logs.png" align="middle" width="800" height="600" alt="Well-logs at KC-151" >

                                    Figure- Well logs from Keathley Canyon 151

**References:**

Bihani A., Pore Size Distribution and Methane Equilibrium Conditions at Walker Ridge Block 313, Northern
Gulf of Mexico, M.S. thesis, University of Texas, Austin, Texas, 2016. doi:10.15781/T2542J80Z

Collett, T. S., Lee, M. W., Zyrianova, M. V., Mrozewski, S. a., Guerin, G., Cook, A. E., and 	Goldberg, D. S. (2012). Gulf of Mexico Gas Hydrate Joint Industry Project Leg II logging-	while-drilling data acquisition and analysis. Marine and Petroleum Geology, 34(1),41-61, 	doi:10.1016/j.marpetgeo.2011.08.003

Ruppel, C., Boswell, R., and Jones, E. (2008). Scientific results from Gulf of Mexico Gas 	Hydrates Joint Industry Project Leg 1 drilling: Introduction and overview. Marine and Petroleum Geology, 25(9), 819–829. doi:10.1016/j.marpetgeo.2008.02.007










