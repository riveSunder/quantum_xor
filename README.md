# Quantum XOR: the learning way

We all know that a single layer perceptron (or a perceptron with multiple linear layers) can't learn to separate the XOR truth table, which is a non-linear function. In conventional artificial neural networks, learning XOR becomes easy with the addition of a hidden layer with a non-linear activation function.


<img src="./figs/noisy_q_xor.gif">
<p align="center"><em>A QNN learns to distinguish the exclusive OR function on noisy data.</em></p>


# Quantum XOR with CNOT

Of course, computing XOR in a differentiable quantum circuit/quantum neural network is no more practical than training a multilayer perceptron to do the same classically. Instead we can use the CNOT gate, a two-qubit quantum gate that flips the second qubit when the first is set. The 4 by 4 matrix for CNOT can be written as: 

<img src="figs/cnot.png">
Writing the truth table for this operation we have: 

<img src="figs/truth_table.png">






