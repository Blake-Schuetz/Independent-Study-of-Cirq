# Independent-Study-of-Cirq
This includes my answers to the workshops offered by Google Quantum AI on using the Cirq SDK for quantum computing research. All notebooks are originally from Google Quantum AI. The changes I made to these notebooks were to fill in an attempted solution to each exercise, as stated in their original sources. 

What I learned:
1.  Create quantum circuits, with and without generator functions and insertion strategies
2.  Create customized gates
3.  Simulate parameterized circuits
4.  Define a phase estimation function
5.  Attempt to create a Quantum Fourier Transform (QFT) function with the option to reverse outputs, implement Phase Estimation on an arbitrary unitary gate, and apply adjacency constraints to QFT and Phase Estimation 


The original notebooks can be found below:
https://quantumai.google/cirq/start/intro
https://quantumai.google/cirq/experiments/textbook_algorithms

Installation & Usage: To open this up, I used Ubuntu to create a Python environment. This was done by opening Ubuntu and placing the following commands:

python3 -m venv venv 

source venv/bin/activate 

jupyter lab --no-browser --ip=0.0.0.0 --port [insert a port number]
