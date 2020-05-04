# A Coupled Analysis of Atmospheric Mass Loss and Tidal Evolution in XUV Irradiated Exoplanets: the TRAPPIST-1 Case Study
##Code, Data, and Extra Figures to accompany the paper

The paper can be found at [this link](BeckerGalloEtAl2020_preprint.pdf). In this paper, we present a coupled analysis of dynamical tidal dissipation and atmospheric mass loss for exoplanets in XUV irradiated environments. As our primary application, we use this model to study the TRAPPIST-1 system, and place constraints on the interior structure and orbital evolution of the planets. We start by reporting on a UV continuum flux measurement for the star TRAPPIST-1, based on 300 ks of Neil Gehrels Swift Observatory data, and which enables an estimate of the XUV-driven thermal escape arising from XUV photo-dissociation for each planet. We also measure the X-ray flaring and non-flaring luminosities, measured from our X-ray detections, of TRAPPIST-1. We then construct a model that includes both atmospheric mass-loss and tidal evolution, and requires the planets to attain their present-day orbital elements during this coupled evolution. We use this model to constrain the tidal structure for each planet. Finally, we use additional numerical models implemented with the Virtual Planet Simulator \texttt{VPLanet} to study ocean retention for these planets using our derived system parameters.

To see how the figures in the paper were made and how the analysis was conducted, [use this Jupyter notebook to re-generate them](MakeFigures.ipynb). This notebook walks through the steps needed to do the analysis, including reducing data, measuring the luminosities, examining the dynamics, and interpreting the VPlanet results. Other important files that can be found in this repository are listed below:

#### [VPlanet Analysis](VPlanetRuns/AtmEsc%2BEqTide)

To see how to run the `vplanet <https://github.com/VirtualPlanetaryLaboratory/vplanet>`_ analysis, [go to this page](VPlanetRuns/AtmEsc%2BEqTide). In our application of VPlanet, we use our measured value of XUV luminosity and combined that with the most likely model for XUV evolution to examine water mass loss on the planets for different internal structures. 

#### [Data](AssortedData)

The data is in folder [AssortedData](AssortedData). This includes all data used in this paper, both new (the SWIFT UVOT/Xray data and numerical results generated in this work) as well as other data we used (filter responses for GALEX and UVOT, and the BHAC 2015 stellar models). 


#### [Extra Figures](ExtraFigures)

Figures that did not make it into the final draft of the paper but may be helpful are found in the folder  [ExtraFigures](ExtraFigures). 


#### [PaperFigures](PaperFigures)

Figures that were included in the manuscript can be found in the folder [PaperFigures](PaperFigures). 




