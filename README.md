# Proof of Concept for the paper "Triangulated Relativistic Quantum Computation: A Curvature--Modulated Unification of Quantum and Relativistic Computing"

## Summary

This Supplementary Material provides the numerical Proof-of-Concept (PoC) accompanying the manuscript, \textit{Triangulated Relativistic Quantum Computation: A Curvature-Modulated Unification of Quantum and Relativistic Computing}, which was submitted to the **Quantum Studies: Mathematics and Foundations** Journal.

The PoC confirms the consistency and operational semantics of the TRQC framework by simulating transport across representative graph families and verifying the core theoretical invariants, including causal order independence, remeshing robustness, and the expected $O(4^N)$ density-matrix scaling. 

We present detailed results for transport metrics and address the reviewer's specific request for peak-over-steps arrival data to mitigate the effects of detector overshoot.

## Source Code and Replication

The complete Python code for the numerical Proof-of-Concept (PoC) is implemented as a self-contained Jupyter Notebook (**proof\_of\_concept.ipynb**). 

All simulations rely on the ``PennyLane`` quantum programming framework (using the default.mixed device for density-matrix evolution) and standard scientific libraries (numpy, scipy, and networkx).

All relevant figures can be found at folder ```figs```

All relevant metrics can be found at folder ```summaries```

Be aware that the provided notebook is full functional and it will create a folder ```artifacts``` weighting more than 3GB, as well as it will re-create the ```figs``` and ```summaries``` folders.


