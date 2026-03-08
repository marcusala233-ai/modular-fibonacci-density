# Modular Constrictions and Asymptotic Density of Goldbach Partitions in Fibonacci Numbers

# Modular Constrictions and Asymptotic Density of Goldbach Partitions in Fibonacci Numbers

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Status: Pre-print](https://img.shields.io/badge/Status-Pre--print-blue.svg)]()
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18912503.svg)](https://doi.org/10.5281/zenodo.SEU_NUMERO_AQUI)


## Abstract
This repository contains the formal research article investigating the intersection of the Fibonacci sequence and Additive Number Theory. Specifically, it explores the subset of even Fibonacci numbers ($F_{3k}$) under the framework of the Goldbach Conjecture ($2N = p_1 + p_2$). 

By projecting the Binet Formula onto the finite field $\mathbb{F}_{11}$, we establish strict topological constrictions. The research demonstrates that prime partitions forming Fibonacci numbers are not statistically independent but orbit specific modular frequencies dictated by the characteristic polynomial of the sequence.

## Core Mathematical Framework

### 1. $\mathbb{F}_{11}$ Isomorphism and Parity Constant
The sequence's roots $\phi$ and $\psi$ are factored within $\mathbb{F}_{11}$, yielding the cyclic parity constant for even Fibonacci numbers:
$$F_{3k} \equiv 3 \cdot (6^k - 9^k) \pmod{11}$$

### 2. Topological Sieve Injection
Applying Dirichlet's Theorem on Arithmetic Progressions and Chen's Sieve, we prove that constituent primes ($p_1, p_2$) of a Goldbach-Fibonacci partition are bounded by the orbital relation:
$$p_1 + p_2 \equiv 3 \cdot (6^k - 9^k) \pmod{11}$$

### 3. Asymptotic Density Formula
Fusing Binet's asymptotic limit with the extended Hardy-Littlewood conjecture, the expected density of prime partitions for a given $F_{3k}$ is derived as:
$$D(F_{3k}) \sim \left( \frac{2 C_2}{\sqrt{5} \cdot 9 (\ln \phi)^2} \right) \cdot \frac{\phi^{3k}}{k^2} \cdot \prod_{p|F_{3k}, p>2} \frac{p-1}{p-2}$$

## Repository Contents
* **`Article_Goldbach_Fibonacci.pdf`**: The complete, peer-review-ready research paper containing all formal proofs, lemmas, and asymptotic derivations.

## License and Copyright
This mathematical framework and the associated article are protected under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)**. 

Under this license, visitors are free to download and share the research paper, provided that:
* **Attribution:** Appropriate credit is given to the original author.
* **NonCommercial:** The material is not used for any commercial purposes.
* **NoDerivatives:** The mathematical derivations, formulas, and text cannot be remixed, transformed, or built upon for distribution without explicit permission.

*Copyright © 2026 Marcus Ala Pedreira Roriz. All rights reserved.*

## Author
**Marcus Ala Pedreira Roriz**
*Instituto de Matemática e Estatística (IME) - Universidade Federal de Goiás (UFG)*
Contact: [marcusala233@discente.ufg.br](mailto:marcusala233@discente.ufg.br)
