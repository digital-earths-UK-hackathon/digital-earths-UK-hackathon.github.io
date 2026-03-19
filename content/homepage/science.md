---
title: "Science Plan"
weight: 8
header_menu_title: "Science Plan"
header_menu: true
---
A K-Scale model hierarchy, encompassing a set of year-long global and regional domain simulations across a range of grid resolutions and science options. This is designed to enable analysis of a range of research questions. This year’s event builds on the [2025 WCRP Global Hackathon](https://www.wcrp-esmo.org/activities/wcrp-global-km-scale-hackathon-2025) which aimed to: drive advances in high-resolution models; to promote and share best practices for coding and workflows; and to foster a global community with open access to datasets. The 2025 event established a number of working groups through the UK event hosted in Oxford.
For this 2026 UK event, the Global to Regional km-scale hackathon, will tackle a range of questions in the context of developing evidence to address two over-arching hypotheses:

A: Better representing mesoscale phenomena, such as details of local-scale convection, feeds back on the large-scale atmospheric circulation.
B: Development of high quality, high-resolution global simulations generates new information that may be of value for enhancing development of machine learning approaches to weather and climate prediction.

A number of data sets will be made available on the JASMIN object store, in HEALPix format, and accessible remotely. Notebooks to perform the analyses above, at least at an initial stage, will be provided to all, including catalogues for data discovery. Observational products will also be provided, e.g. ERA5, IMERG, CERES. Many of the more complex data sets, e.g. TC tracks, MCS tracks, will be provided before the event. Multiple working groups will be formed around topics linked to addressing the hypotheses above, and will work together at the venue.
Potential working group themes might include:
-	Tropical and Extra-tropical cyclones 
-	Monsoon circulations and energetics 
-	Tropical wave activity, propagation and tele-connections 
-	Mesoscale convective systems 
-	Upscale influence of mesoscale phenomena on the large-scale circulation – utilising the local scale-to-scale energy transfer tool [LoSSETT](https://github.com/ElliotMG/LoSSETT)
-	Land surface interactions 
-	Clouds and radiation
-	Further topics of interest to be added ahead of and during the hackathon
Across each of these groups, it may be useful to consider:
1)	How do the characteristics of the phenomena of interest differ between global and tropics-wide domain simulations with explicit representation of convection [i.e. using the RAL3.3 science configuration] relative to a benchmark high-resolution weather/climate configuration with parametrized convection [GAL9]?
2)	What impact does use of a new convection parametrization scheme (CoMorphA, adapted to higher resolution) have on results?
3)	How sensitive are representation of regional phenomena to the domain extent of high-resolution simulations – are there notable differences between global and tropics-wide simulations with explicit convection to benchmark regional Limited Area Models using the same science configuration?
4)	How do biases evident in the hierarchy simulations compare to any known persistent biases related to phenomena of interest in coarser resolution climate models? Are there any sensitivities (e.g. magnitude, sign, extent) to the choice of science configuration, domain extent, or grid resolution of the 1-year hierarchy simulations?
5)	Given the majority of current generation global machine-learning weather prediction models are trained using ERA5 reanalysis data, how does the representation of phenomena differ in the K-Scale hierarchy simulations? Are both or either representations physically realistic when compared to available observations?

<!---
The science topics for all nodes fall under two umbrella themes: 1) organised travelling convection and 2) circulation, which are closely related. As part of the investigations, there are working groups on tracking (of TCs, MCSs, MJO); characteristics of precipitation, e.g. large scale versus convective, spectra, diurnal cycle; atmospheric blocking; air-sea and land-atmosphere coupling, etc.
The UK plans to explore a hierarchy of simulations from the Met Office K-scale project, from global to regional, to investigate:

1. Convection under a range of simulation approaches, e.g. the dependence on resolution, domain size, type of convective parametrisation
2. Weather systems, such as TCs and MCSs, and their interaction with the large scale circulation
3. Upscale effects of a number of phenomena, with initial focus on TCs, and how they affect the large scale circulation
4. Cloud tracking across models using state-of-the art tools (e.g. PyFLEXTRKR,  tobac) and will expand on analysis of cloud spatial structure using multifractal and computer vision approaches. 
5. The Oxford group will also work on global km-scale ICON runs with explicit aerosols conducted within NextGEMS.

Science Questions:

1. Are weather systems, and their interactions with the large-scale flow, significantly different, depending on the use of convective parametrisation in the various DYAMOND-3 simulations?
2. Can we detect significant contributions to the large-scale flow by the existence of MCSs and TCs, including the ones in the top categories?
3. What are the characteristics of precipitation under different treatments of resolution, parametrisation (including aerosol), coupling?
4. Having established the degree of simulation fidelity, based on the analyses of phenomena and processes above, are any of the participating models good/valuable candidates for ML training?
5. What new science emerges robustly across the models taking part in DYAMOND-3? Examples:
    1. strength and process-chain for UPSCALE effects emerging from analysis of TCs and MCSs
    2. quality of the precipitation fields as revealed by comparison with latest observations, and in preparation for EarthCARE
    3. are there universal lessons on the value of simulation at these scales, e.g. in terms of results that are robust across model families?

Approach:
A number of data sets will be made available on the JASMIN object store, in HEALPix format, and accessible remotely. Notebooks to perform the analyses above, at least at an initial stage, will be provided to all, including catalogues for data discovery. Observational products will also be provided, e.g. ERA5, IMERG, CERES. Many of the more complex data sets, e.g. TC tracks, MCS tracks, will be provided before the event.
Multiple working groups of 5 or more individuals  will be formed around the topics above, and will work together at the venue, as well as identify equivalent groups at other nodes to exchange information with on a daily basis.
-->
