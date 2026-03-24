---
title: A quantitative analysis of Koopman operator methods for system identification and predictions

authors:
  - me
  - ezuazua

date: 2022-09-05

publication_types: ["article-journal"]

publication: "Comptes-Rendus Mécanique"
publication_short: "CRM"

abstract: >
  We give convergence and cost estimates for a data-driven system identification method: given an unknown dynamical system, the aim is to recover its vector field and its flow from trajectory data. It is based on the so-called Koopman operator, which uses the well-known link between differential equations and linear transport equations. Data-driven methods recover specific finite-dimensional approximations of the Koopman operator, which can be understood as a transport operator. We focus on such approximations given by classical finite-elements spaces, which allow us to give estimates on the approximation of the Koopman operator as well as the solutions of the associated linear transport equation. These approximations are thus relevant objects to solve the system identification problem. We then analyze the convergence of a variant of the generator Extended Dynamic Mode Decomposition (gEDMD) algorithm, one of the main algorithms developed to compute approximations of the Koopman operator from data. We find however that, when combining this algorithm with classical finite elements spaces, the results are not satisfactory numerically, as the convergence of the data-driven approximation is too slow for the method to benefit from the accuracy of finite elements spaces. In particular, for problems in dimension 1 it is less efficient than direct interpolation methods to recover the vector field. We provide some numerical examples to illustrate this last point.

links:
  - name: Preprint
    url: https://hal.archives-ouvertes.fr/hal-03278445
  - name: PDF
    url: https://comptes-rendus.academie-sciences.fr/mecanique/item/CRMECA_2023__351_S1_A3_0/

draft: false
---
