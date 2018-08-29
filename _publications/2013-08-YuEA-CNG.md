---
title: "Parameterization for distributed watershed modeling using national data and evolutionary algorithm"
collection: publications
date: 2013-05-29
authors: Yu, X., G. Bhatt, C. Duffy, and <b>Y. Shi</b>
venue: "Computers & Geosciences"
paperurl: https://doi.org/10.1016/j.cageo.2013.04.025
doi: 10.1016/j.cageo.2013.04.025
volume: 58
pages: 80&ndash;90
abstract: "Distributed hydrologic models supported by national soil survey, geology, topography and vegetation data products can provide valuable information about the watershed hydrologic cycle. However numerical simulation of the multi-state, multi-process system is structurally complex and computationally intensive. This presents a major difficulty in model calibration using traditional techniques. This paper presents an efficient calibration strategy for the physics-based, fully coupled, distributed hydrologic model Penn State Integrated Hydrologic Model (PIHM) with the support of national data products. PIHM uses a semi-discrete Finite Volume Method (FVM) formulation of the system of coupled ordinary differential equations (e.g. canopy interception, transpiration, soil evaporation) and partial differential equations (e.g. groundwater-surface water, overland flow, infiltration, channel flow, etc.). The matrix of key parameters to be estimated in the optimization process was partitioned into two groups according to the sensitivity to difference in time scales. The first group of parameters generally describes hydrologic processes influenced by hydrologic events (event-scale group: EG), which are sensitive to short time runoff generation, while the second group of parameters is largely influenced by seasonal changes in energy (seasonal time scale group: SG). The Covariance Matrix Adaptation Evolution Strategy (CMA-ES) is used to optimize the EG parameters in Message Passing Interface (MPI) environment, followed by the estimation of parameters in the SG. The calibration strategy was applied at three watersheds in central PA: a small upland catchment (8.4 ha), a watershed in the Appalachian Plateau (231 km<sup>2</sup>) and the Valley and Ridge of central Pennsylvania (843 km<sup>2</sup>). A partition calibration enabled a fast and efficient estimation of parameters."
---
