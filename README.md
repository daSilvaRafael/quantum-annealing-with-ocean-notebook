<!--- [![Open in Leap IDE](https://cdn-assets.cloud.dwavesys.com/shared/latest/badges/leapide.svg)](  https://ide.dwavesys.io/#https://github.com/dwave-examples/factoring-notebook)[![Linux/Mac/Windows build status](  https://circleci.com/gh/dwave-examples/factoring-notebook.svg?style=shield)](  https://circleci.com/gh/dwave-examples/factoring-notebook) --->

# Quantum Annealing with Ocean

This jupyter notebook is a supplementary resource to the author’s paper _Annealing Quantum Computing: An Overview_. The paper aims to provide an accessible overview of annealing quantum computing. We give high-level explanations of the key quantum properties that are leveraged by a quantum annealer, along with the quantum mathematical formalism involved and references for further reading.

The notebook has the following sections:

   1. Ising and QUBO model
   
       1.1 Exact solution
       
       1.2 Simulated annealing
       
   2. Problem to QUBO
       
       2.1 Exact solver
       
       2.2 Run on a quantum annealer processor
       
       2.3 Run on a Hybrid solver

   3. Problem constrains
   
       3.1 Run on a Hybrid CQM solver
   
   4. Embedding


## Installation

<!--- You can run this example [in the Leap IDE](https://ide.dwavesys.io/#https://github.com/dwave-examples). --->

Install requirements locally (ideally, in a virtual environment):

    pip install -r requirements.txt

<!--- ## Usage

To enable notebook extensions[^1]:

```bash
jupyter contrib nbextension install --sys-prefix
jupyter nbextension enable toc2/main
jupyter nbextension enable exercise/main
jupyter nbextension enable exercise2/main
jupyter nbextension enable python-markdown/main

``` --->


To run the notebook:

```bash
jupyter notebook
```

<!--- [^1]: Leap's IDE, which runs VS Code, does not support all notebook extensions. --->

## References

R. Pereira da Silva (2023), [_Annealing Quantum Computing: An Overview_](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4501788) SSRN Electronic Journal

## License

Released under the Apache License 2.0. See LICENSE file.
