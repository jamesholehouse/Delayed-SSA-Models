# Delayed-SSA-Models
This code allows one to simulate the delayed stochastic simulation algorithm (DSSA) for the mechanistic and delayed-telegraph models of gene expression in https://www.biorxiv.org/content/10.1101/2021.06.08.447592v1.abstract. Descriptions of each file are provided below.

- `DSSA-Mech.jl`: Julia code that allows one to simulate the mechanstic model in Eq. (1).
- `DSSA-delayed-telegraph.jl`: Julia code that allows one to simulate the delayed telegraph model in Eq. (2).
- `Example-SSA-mechanistic.ipynb`: Exhibits usage of the DSSA code from `DSSA-Mech.jl`.
- `Example-SSA-delayed-telegraph.ipynb`: Exhibits usage of the DSSA code from `DSSA-delayed-telegraph.jl`.

The DSSA here utilises Algorithm 2 of Barrio, Manuel, et al. "Oscillatory regulation of Hes1: discrete stochastic delay modelling and simulation." PLoS computational biology 2.9 (2006): e117.

For queries on the code above please contact james.holehouse@ed.ac.uk or jamesholehouse1@gmail.com. For non-code related queries please contact ramon.grima@ed.ac.uk.
