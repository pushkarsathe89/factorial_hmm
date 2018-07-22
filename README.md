# FactorialHMM

FactorialHMM is a Python package for fast exact inference in Factorial Hidden Markov Models. 

Our package allows:
* Simulating directly from the model 
* Simulating from the posterior distribution of states given the observations
* Calculating the (Viterbi) sequence of states with the largest posterior probability
* Calculating the Forward-Backward algorithm, and in particular likelihood of the data and the posterior probability (given all observations) of the marginal and joint state probabilities
as well as additional HMM-related procedures.

The running time and space requirement of all procedures is linear in the number of possible states. This package is highly modular, providing the user with maximal flexibility for developing downstream applications.

## Installation

Simply download the `factorial_hmm.py` file, add its location to `sys.path` (e.g., `sys.path.append(path_to_dir)`), and import the library.

## Usage

The full documentation is available at the [Wiki section](https://github.com/myheritage/factorial_hmm/wiki).