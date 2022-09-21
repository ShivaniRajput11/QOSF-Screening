# QOSF-Screening

## Reference link:

https://arxiv.org/pdf/quant-ph/0008033.pdf

https://arxiv.org/pdf/1706.05113.pdf

https://arxiv.org/pdf/1411.5949.pdf


Task 1 Multiplier
To make a multiplier, for this we design the input of two positive integers to a function and this function will process a quantum algorithm that makes the multiplier (see Draper adder) and returns the result in an integer.

you cannot use any implementation already designed by the framework


## def multiplier(int:number_1, int ,number_2):
     “””
## number_1 : integer positive value that is the first parameter to the multiplier function,
## number_2 : integer positive value that is the second parameter to the multiplier function.
## the positive integer value of the multiplication between number_1 and number_2
     “””

## use a framework that works with quantum circuits, qiskit, cirq, pennylane, etc. 


## define a quantum circuit to convert the integer values in qubits, example bases encoding 
## basis encoding: n bits are equals to a state of n qubits, example 
## The integer value 3 convert to a binary string that is 11, the basis encoding is |11⟩
     
## use the state of the art to check the possibles ways to design a multiplier

## Return the result of the quantum circuit into an integer value

## consider print your quantum circuit,


Example:

A = multiplier(5,6)
print(A)

30

Bonus: 
Use your proposal to design different inputs, and check the limitations of your simulator and framework, consider number of qubits, time of execution, the depth of the quantum circuit and number of the gates.

