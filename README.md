# QCircuitOptimization

Quantum circuits model a sequence of operations to be performed by a quantum computer. CNOT Dihedral circuits are an important class of such quantum circuits. This project demonstrated that the cost of a quantum circuit could be optimized by reducing the # of T gates through ideas of group theory. This was proven through the below steps:  

i. We showed that every CNOT Dihedral circuit can be modeled by a phase polynomial . 
ii. In turn, the phase polynomials can transformed and factorized into tensor/matrix . 
iii. We used Lempel algorithm to obtain optimal solution for the quantum circuit by reducing the T-count. We also outlined a step-by-step approach to implement Lempel Algorithm . 
iv. Using a concept called ‘Clifford Equivalence’ (which is based on ‘Signature Tensors’), we showed that the optimized solution was equivalent to the original quantum circuit.  

The steps are detailed in the report uploaded.
