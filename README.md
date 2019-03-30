# Quantum XOR: the learning way

We all know that a single layer perceptron (or a perceptron with multiple linear layers) can't learnt to separate the XOR truth table, which is a non-linear function. In conventional artificial neural networks, learning XOR becomes easy with the addition of a hidden layer with a non-linear activation function.

Likewise implementing a classical XOR in a quantum circuit can be implemented as <a href="https://en.wikipedia.org/wiki/Toffoli_gate">Toffoli gate</a>, but it requires a minimum of 6 CNOTs and quite a few T and Hadamard gates arranged on 3 wires. Instead we can teach a "quantum neural network" to discriminate XOR on just two wires. This isn't necessarily better or more elegant than the Toffoli gate, but we want to do it anyway.


<img src="./figs/noisy_q_xor.gif">
<p align="center"><em>A QNN learns to distinguish noisy data in an XOR way.</em></p>

