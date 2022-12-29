# Hybrid quantum gap estimation algorithm

This is the Qiskit code used to generate data and figures in the paper 
"A Compact Noise-Tolerant Algorithm for Unbiased Quantum Simulation Using Feynman's $i\eta$ Prescription"
by Woo-Ram Lee, Ryan Scott, and V. W. Scarola (https://arxiv.org/abs/2212.14039).

One can run this code on the IBMQ device with a certain choice of backends (here set to "ibmq_manila" by default).
An example plot was included at the end of this code to reproduce the case of M = 16 in Fig. 2(d) of the paper.
Other plots can be reproduced in the same way but with different choices of parameters.
To reproduce the middle and bottom panels in Fig. 3, one needs another code for linear regression, which is not provided here.
