---
layout: post
title: "Mean Field Theory from Relative Entropy"
---
Mean field theory allows us to obtain a simplified partition function.
We will motivate this and provide an example.
In statistical physics, one would like to evaluate partition functions.
However, sometimes this evaluation is difficult
because of a "complicated" Hamiltonian.
In mean field theory, one replaced the "complicated" Hamiltonian with a "simple" one.
E.g. take the classical Ising model with
\begin{align}
    H(s) = - J \sum_{<ij>} s_i s_j -h \sum_i s_i,
\end{align}
where the $s_i \in \{\pm 1\}$ are spins associated to a site $i$ in a lattice of $N$ sites.
In mean field theory, this Hamiltonian is replaced with
\begin{align}
    H(m) = - \frac{N}{2} J m(s)^2 - N h m(s),
\end{align}
where
\begin{align}
    m(s) = \frac{1}{N}\sum_i s_i,
\end{align}
can be thought of as an effective magnetization.
Using these two Hamiltonians, one could evaluate the partition function
\begin{align}
    Z = \sum e^{-\beta H}.
\end{align}
There, in the case of the classical Ising model, one has a sum over all possible spin configurations.
However, for mean field theory, one has a sum over all possible effective magnetizations. 