# Measure-Theoretic Anti-Causal Representation Learning

**NeurIPS 2025 Project Page**

[![Project Page](https://img.shields.io/badge/Project-Page-blue)](https://armanbehnam.github.io/anticausal-neurips2025/)
[![Paper](https://img.shields.io/badge/Paper-PDF-red)]()
[![Code](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/ArmanBehnam/ACIA)
[![arXiv](https://img.shields.io/badge/arXiv-2025-orange)]()

## Overview

This repository contains the project website for **ACIA (Anti-Causal Invariant Abstractions)**, a novel measure-theoretic framework for anti-causal representation learning accepted at NeurIPS 2025.

**Authors:** [Arman Behnam](https://armanbehnam.github.io/) and [Binghui Wang](https://wangbinghui.net/)

## Abstract

Causal representation learning in the anti-causal setting—labels cause features rather than the reverse—presents unique challenges requiring specialized approaches. We propose ACIA, a novel measure-theoretic framework that employs a two-level design: low-level representations capture how labels generate observations, while high-level representations learn stable causal patterns across environment-specific variations.

## Project Structure

```
anticausal-neurips2025/
├── fig/                          # Figures and visualizations
├── index.html                    # Main landing page
├── introduction.html             # Introduction section
├── background.html               # Measure theory & causality background
├── problem.html                  # Problem formulation
├── theoretical.html              # Theoretical framework (Theorems 3 & 4)
├── properties.html               # Mathematical properties & proofs
├── exp_setup.html                # Experimental setup
├── exp_results.html              # Experimental results & visualizations
├── references.html               # Bibliography
├── conclusion.html               # Conclusion
├── appendix_related_work.html    # Related work appendix
└── README.md                     # This file
```

## Key Features

- **Two-Level Representation Learning:**
  - Low-level ($\phi_L$): Captures anti-causal structure ($Y \rightarrow X \leftarrow E$)
  - High-level ($\phi_H$): Distills environment-invariant causal features

- **Interventional Kernels:** Handles both perfect and imperfect interventions

- **Theoretical Guarantees:**
  - Convergence rates
  - OOD generalization bounds
  - Environmental robustness

## Results

- **CMNIST/RMNIST:** 99%+ accuracy with perfect environment independence
- **Ball Agent:** 99.98% accuracy with near-perfect invariance
- **Camelyon17:** 84.40% accuracy (19% improvement over best baseline)

## Installation

Visit the [ACIA code repository](https://github.com/ArmanBehnam/ACIA) for implementation:

```bash
git clone https://github.com/ArmanBehnam/ACIA
cd ACIA
pip install -e .
pip install -r requirements.txt
```

## Usage

To view the project website locally:

```bash
# Open index.html in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

Or visit the live site: [https://armanbehnam.github.io/anticausal-neurips2025/](https://armanbehnam.github.io/anticausal-neurips2025/)

## Citation

```bibtex
@inproceedings{behnam2025anticausal,
  title={Measure-Theoretic Anti-Causal Representation Learning},
  author={Behnam, Arman and Wang, Binghui},
  booktitle={Advances in Neural Information Processing Systems},
  year={2025}
}
```

## Acknowledgments

This work was supported by the Cisco Research Award and the National Science Foundation under Grant Nos. ECCS-2216926, CCF-2331302, CNS-2241713, and CNS-2339686.

## Contact

- Arman Behnam: [Website](https://armanbehnam.github.io/)
- Binghui Wang: [Website](https://wangbinghui.net/)

## License

This project website is available under the MIT License.