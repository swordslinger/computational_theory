# Computational Theory Tasks
This repository contains my submission for the Computational Theory module as part of the Bachelor of Science (Honours) in Computing and Software Development.

## Table of Contents
- [Introduction](#introduction)
- [Installation and Usage](#installation-and-usage)
- [Dependencies](#dependencies)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
This repository contains a **tasks.ipynb** which contains:
  1. Implementations for the rotl, rotr, ch, and maj bitwise operators.
  2. A short analysis on why hash functions use 31 as a multiplier and 101 as a hash table.
  3. A Python function that prints the SHA-256 padding for a file.
  4. An implementation of the Sieve of Eratosthenes algorithm to generate the first 100 prime numbers.
  5. An implementation of wheel factorization to generate the first 100 prime numbers.
  6. Calculations to compute the first 32 bits of the fractional parts of the square roots of the first 100 prime numbers.
  7. Calculations to find words that have the biggest number of '0' bits at the beginning of their SHA256 digest.
  8. A Turing machine simulator and the state table for adding 1 to a binary number on the tape.
  9. A bubble sort algorithm implementation that's modified to count the comparisons made during sorting and prints each permutation and the number of comparisons required to sort it.

 **example.txt** which contains 'abc' that is used in task 3.

 **.gitIgnore** which excludes unnecessary files and reduces commit sizes.

 **requirements.txt** which contains the packages needed to run this notebook.

## Installation and Usage
Step by step instructions on how to run tasks.ipynb:
1. Clone the repository:
   ```bash
   git clone https://github.com/swordslinger/computational_theory
2. Navigate to the project directory:
    ```bash
    cd computational_theory
3. Install dependencies from requirements.txt:
   ```bash
    pip install -r requirements.txt
4. Download list of english words.
   ```bash
    curl -o words.txt https://raw.githubusercontent.com/dwyl/english-words/master/words.txt
5. Install Jupyter Notebook:
   ```bash
    pip install notebook
6. Start Jupyter notebook:
    ```bash
    jupyter notebook.
Restart the kernel.
Run all cells.

## Dependencies
Dependencies for tasks.ipynb as per requirements.txt:

- numpy: Used heavily in task 5 for efficient array handling.
- words.txt Used in task 7.

## License
No Licenses.

## Acknowledgements
For this project I used a combination of ChatGPT and Copilot for grammar, punctuation, spelling, troubleshooting and tab completion. As well as the course materials for the different tasks. [course materials for computational theory](https://github.com/ianmcloughlin/computational_theory/tree/main/materials)
