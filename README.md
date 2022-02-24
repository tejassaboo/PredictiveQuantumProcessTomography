# QiskitBiskitGlobal - Predictive Quantum Process Tomography
IBM Global Hackathon Project

Created by:
Adarsh Hullahalli,
Pranav Eswaran, 
Tejas Saboo,
Varun Nayak,
Ayush Bhattacharya

We investigated efficient algorithms for identifying and correcting errors caused by noise in quantum circuits using twirling and ML. First, we generated a dataset of 825 Pauli Transfer Matrices to train a non-linear neural network with a fidelity loss function by iterating through 25 levels of amplitude damping and dephasing for 33 randomized circuits and performing quantum process tomography. We simulated amplitude damping with a controlled-Ry gate targeting the environment followed by a controlled-NOT gate targeting the qubit and simulated dephasing with a Ry gate on the environment followed by a CZ gate on the pair. 

We were awarded 2nd Place at UT Qiskit Fall Fest Quantum Computing Hackathon and advanced to IBM Qiskit Global Invitational Hackathon.

Tech: Python, Qiskit, PyTorch, SymPy, NumPy, Matplotlib, pandas, scikit-learn
<br>
