# Minimal BCM/STDP Membrane Model
This repository provides a **minimal working implementation** of the
voltage-based BCM/STDP model that reproduces Figures 1–3 from the
reference literature (https://link.springer.com/chapter/10.1007/978-3-642-02490-0_17)

这是一个最小模型用于复现论文中的内容，仅供各位参考
## ✨ Features
- Reproduces **STDP window**, **BCM-like frequency dependence**, and **triplet plasticity**
- Single-file implementation (`main.py`)
- No external dependencies beyond `numpy` and `matplotlib`
- Easily modifiable for testing different learning rules or parameters
## Usage
1. Open [`main.txt`](main.txt) in this repository.  
2. Copy all the code and paste it into a local Python environment (e.g. Spyder, VSCode, or Jupyter Notebook).  
   - Or simply download the file and rename it as `main.py`.
3. Run the script — it will automatically generate all three figures:
   - **Figure 1:** STDP window  
   - **Figure 2:** BCM-like frequency dependence  
   - **Figure 3:** Triplet protocol

The only packages you need are the standard scientific stack:

```python
import numpy as np
import matplotlib.pyplot as plt

