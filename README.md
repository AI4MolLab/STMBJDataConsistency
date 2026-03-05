# STMBJDataConsistency
Unified Statistical Framework for Quantitative Assessment of Data Consistency in Single-Molecule Electronics

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
- **Description:** .

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
- Zhichao Pan`(panzhichao@guet.edu.cn)` 
