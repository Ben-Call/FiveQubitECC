# FiveQubitECC
Implementation of the five qubit error correcting code.

This contains a python notebook with an implementation of the five qubit error correcting code. It corrects any single gate error on one of the qubits.

Of possibly independent interest is an implementation of a circuit which implements single qubit gate errors on a circuit of arbitrary size for any given error probability. There is also a function which implements both logical 1 and logical 0 for this error correcting code.

In addition to these implementations, there is also some analysis of the success rates of the error corrections, evaluated using matplotlib. This analylsis is imperfect due to computational time limitations, but it approaches the general idea of what we should expect.
