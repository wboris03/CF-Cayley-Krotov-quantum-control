# CF-Cayley-Krotov-quantum-control
This repository contains the code used to generate the numerical results in the paper

**Structure-Preserving Cayley Methods for Krotov-Type Algorithms in Quantum Optimal Control**

Proceeding paper, ECC2026.

## Overview

The repository provides implementations of:
- commutator-free exponential schemes,
- Cayley-Magnus schemes,
- commutator-free Cayley (CF-Cayley) schemes,
- CaylPol method for the nonlinear case,
- Runge-Kutta-Munthe-Kaas method of order 4,
- Krotov-type optimal control iterations for linear quantum control problems.

The examples include:
- a linear Schrödinger control problem with structured potential,
- a nonlinear Gross-Pitaevskii equation.

## Installation

Create a Python environment and install dependencies:

```bash
pip install -r requirements.txt
