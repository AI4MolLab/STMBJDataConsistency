# STMBJDataConsistency
Unified Statistical Framework for Quantitative Assessment of Data Consistency in Single-Molecule Electronics

## Overview

<img width="9444" height="5563" alt="Figure1" src="https://github.com/user-attachments/assets/7495c3df-c9b5-414f-b4ca-0f763a2f0e5a" />
We introduce a Unified Statistical Framework to quantitatively assess data consistency in single-molecule break junction (SMBJ) experiments.
The framework integrates NHST, TOST equivalence testing, and Bayesian inference,
transitioning the field from semi-quantitative parameter comparison to probabilistic metrology and providing a standardized toolset for validating single-molecule devices.

  - **Large-N Robustness**: mitigates NHST over-sensitivity in high-throughput data.
  - **Equivalence Decision (TOST)**: gives an objective consistency judgment within a predefined equivalence bound.
  - **Bayesian Consistency Probability**: reports posterior evidence (e.g., ROPE/HDI) to quantify uncertainty.
  - **Sequential Stopping Rule**: determines sufficient sample size via evidence convergence.

This repository provides an end-to-end pipeline for statistical testing and visualization, including NHST, TOST, Bayesian ROPE/HDI,
and Bayesian sequential analysis, validated on SMBJ datasets such as NiS<sub>4</sub> (multi-bias conditions), MoZn, and OPE2.

## Dependencies

- Python: **3.8.18**
- Required packages:

  - numpy==1.23.5
  - pandas==2.0.3
  - matplotlib==3.7.2
  - seaborn==0.13.1
  - scipy==1.10.1
  - pymc==5.6.1
  - arviz==0.15.1
  - pytensor==2.12.3
  - ipython==8.12.3
  - tqdm==4.67.2

Install via:

```bash
pip install -r requirements.txt
```

## Code / Notebooks

### Simulated Data
- **File:** `simulated_data.ipynb`  
- **Description:** Generation and visualization of simulated data, including peak-position sampling and distribution analysis.

### Statistical Testing
- **Files:**  
  - `main(MoZn).ipynb`  
  - `main(OPE2).ipynb`  
  - `main(NiS4-0.1V).ipynb`  
  - `main(NiS4-0.2V).ipynb`
  - `main(NiS4-0.3V).ipynb`
  - `main(NiS4-0.4V).ipynb`
  - `main(NiS4-0.1V~0.2V).ipynb`
  - `main(NiS4-0.1V~0.4V).ipynb`
- **Description:** End-to-end statistical testing workflow for different datasets/conditions, including significance testing, equivalence testing, Bayesian inference, and Bayesian sequential analysis.

## Data
 
Datasets are not included in this repository due to file size limitations.

## Authors

- Ziyang Wang
- Bailin Gao
- Liying Wang
- Hengzhi Huang
- Zhichao Pan (panzhichao@guet.edu.cn) 
