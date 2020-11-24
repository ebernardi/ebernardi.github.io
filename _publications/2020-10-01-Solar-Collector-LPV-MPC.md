---
title: "Nonlinear Temperature Regulation of Solar Collectors with a Fast Adaptive Polytopic LPV MPC Formulation"
collection: publications
venue: 'Solar Energy'
authors: Hugo A. Pipino, Marcelo M. Morato, <b>Emanuel Bernardi</b>, Eduardo J. Adam, and Julio E. Normey-Rico
date: October 2020
volume: 209C
issn: 0038-092X
doi: <a href="https://doi.org/10.1016/j.solener.2020.09.005">10.1016/j.solener.2020.09.005</a>
---
Abstract: Temperature control in solar collectors is a nonlinear problem: the dynamics of temperature rise vary according to the fluid flowing through the collector and to the temperature gradient along the collector area. In this way, this work investigates the formulation of a Model Predictive Control (MPC) application developed within a Linear Parameter Varying (LPV) formalism, which serves as a model of the solar collector process. The proposed system is an adaptive MPC, developed with terminal set constraints and considering the scheduling polytope of the model. At each instant, two Quadratic Programming (QPs) programs are solved: the first considers a backward horizon of $N$ steps to find a virtual model-process tuning variable that defines the best LTI prediction model, considering the vertices of the polytopic system; then, the second QP uses this LTI model to optimize performances along a forward horizon of $N$ steps. The paper ends with a realistic solar collector simulation results, comparing the proposed MPC to other techniques from the literature (linear MPC and robust tube-MPC). Discussions regarding the results, the design procedure and the computational effort for the three methods are presented. It is shown how the proposed MPC design is able to outrank these other standard methods in terms of reference tracking and disturbance rejection.

Keywords: Model Predictive Control; Linear Parameter Varying Systems; Quadratic Programming Problem; Tube MPC; Solar Collector.

DOI: <a href="https://doi.org/10.1016/j.solener.2020.09.005">10.1016/j.solener.2020.09.005</a>

Recommended citation: Hugo A. Pipino, Marcelo M. Morato, Emanuel Bernardi, Eduardo J. Adam and Julio E. Normey-Rico. "Nonlinear Temperature Regulation of Solar Collectors with a Fast Adaptive Polytopic LPV MPC Formulation". In: <i>Solar Energy</i> 209C (2020), pp. 214-225. ISSN: 0038-092X. DOI: 10.1016/j.solener.2020.09.005.