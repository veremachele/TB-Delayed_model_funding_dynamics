 A Mathematical Model of TB Transmission Dynamics Incorporating Delays in Funding and Treatment Programs

Authors details: V.M. Mbalilo¹, F. Nyabadza¹˒², S.P. Gatyeni¹  
¹ Department of Mathematics and Applied Mathematics, University of Johannesburg, South Africa  
² Institute of Research and Professional Training, Emirates Aviation University, Dubai International Academic City, UAE  
Corresponding author: fnyabadza@uj.ac.za  

 Overview

This repository is associated with the research paper: A Mathematical Model of TB Transmission Dynamics Incorporating Delays in Funding and Treatment Programs.

The study develops a delay differential equation (DDE) model to investigate tuberculosis (TB) transmission dynamics while incorporating two critical time delays:

- Funding response delay (\(\tau_1\))
- Treatment initiation delay (\(\tau_2\))

The model is calibrated using South African TB incidence data (2000–2023) to examine the impact of delays on disease dynamics, stability, and control strategies.


 Key Features of the Model

- Incorporation of funding and treatment delays
- Analysis of disease-free and endemic equilibria
- Computation of the basic reproduction number (\(\mathcal{R}_0\))
- Stability analysis using Routh–Hurwitz criteria
- Investigation of delay-induced Hopf bifurcation
- Sensitivity analysis of key epidemiological and control parameters
- Numerical simulations using MATLAB (`dde23` solver)

 Main Findings

- Short delays lead to convergence toward a stable endemic equilibrium.
- Critical delay thresholds can induce Hopf bifurcation, leading to oscillatory TB dynamics.
- Treatment delay (\(\tau_2\)) has a stronger destabilizing effect than funding delay (\(\tau_1\)).
- Key parameters influencing TB control include:
  - Prevention efficiency (\(\alpha\))
  - Treatment rate (\(\gamma\))
  - Funding responsiveness (\(\omega\))




 Data Availability

The datasets and MATLAB code supporting this study are publicly available in this repository.


 Contact: 
For inquiries, please contact: fnyabadza@uj.ac.za
