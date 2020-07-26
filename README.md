# Physical Statistic Simulation of the Number of States and Entropy for an Isolated System: entropy_isolated

This repository contains a Jupyter Notebook to simulate the number of states and the entropy of an isolated system using physical statistic arguments.

# Problem Statement

Let them be identical confetti tiles representing individual particles, one per confetti tile. Each particle can have associated with a specific energy that will correspond to a particular value within a discrete number of values ​​$\{E_1, E_2, ..., E_n, ..., E_N\}$. Note that $N$ is the number of energies accessible to the particles, no particle can have a different energy from that of the discrete values.

For a system made up of $M$ particles (one confetti for each one of them), with energy $E = En.sum()$, where each value $En = E_n$ represents the energy of the individual particle, the number of different possible configurations (microstates) of $M$ particles, such that the energy $E$ is the same, is known as the number of states and is represented by $\Omega(E)$.  However, in this simulation, we get the number of occurrences $\Omega'$, that is proportional to the number of states, i.e., $\Omega' = \gamma \Omega$.

Each particle is assumed to be indistinguishable from another particle; therefore, anyone can have a particular energy value $En$. For each energy value of the system $E = En.sum ()$, we have one or more microstates, characterized in that the sum of the energy of the particles equals the value $E$.

It is convenient to use the notation $(n_1, n_2, n_N)$ to enumerate a microstate, where $n_1$ is the number of particles with energy $E_1$ and thus for the other possible energies. For example, suppose that the energy values ​​that the five particles of a system can take are $\{1, 4, 9\}$ in $eV$, so a certain microstate could be $(1, 4, 0)$, another would be $(5, 0, 0)$. In the example, both microstates correspond to different energies, but each particle take the energy of $1 eV$. For this example, the number of states with energy $E = 5 eV$ will be $\Omega (5eV) = 2$ and will correspond to the microstates $(5, 0, 0)$ and $(4, 1, 0)$.

Since for each microstate we have a specific energy $E$, the notation can be simplified by leaving only the non-zero values, for example, instead of $(5, 0, 0)$ we would have $[5]$ and instead of $(4, 1, 0)$, we would have $[4, 1]$.  Note: here, the numbers in brackets "$[$ $]$" corresponds with a Python list.

# Licence

This work is under the MIT license.

# How to cite this work?

Miranda, D. 2020, Physical Statistic Simulation of the Number of States and Entropy for an Isolated System, v1.0, Zenodo, doi:

## DOI

## BibTeX
@misc{Miranda2019,
    author       = {David Miranda},
    title        = {{Physical Statistic Simulation of the Number of States and Entropy for an Isolated System}},
    month        = jul,
    year         = 2020,
    doi          = {},
    version      = {1.0},
    publisher    = {Zenodo},
    url          = {}
    }