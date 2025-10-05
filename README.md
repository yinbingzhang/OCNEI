# OCNEI: Overlapping Community and Neighborhood Entropy-based Influence

This repository contains a demonstration version of the MATLAB implementation developed for the paper:

“Overlapping Community and Entropy of Neighborhood Information for Identifying Influential Nodes in Complex Networks.”

---

## 1. Overview
The OCNEI algorithm integrates overlapping community structures with neighborhood information entropy to identify influential nodes in complex networks.  
This repository provides a reproducible experimental framework that replicates the main results presented in the study.

---

## 2. System Requirements
- Software: MATLAB R2021a or later  
- Dependencies: No additional toolboxes are required beyond the MATLAB standard library  
- Operating System: Windows, macOS, or Linux

---

## 3. How to Execute the Demo

1. Launch MATLAB and navigate to the project directory.  
2. Run the following command in the MATLAB Command Window:  
   ```matlab
   main.m
   ```
3. When prompted, select the desired dataset from the available list.  
   - All datasets are located in the `datasets/` folder and are provided in their raw form, as used in the experiments.  
4. The program will automatically execute the OCNEI algorithm and produce key evaluation metrics, including node influence rankings and performance indicators.

---

## 4. Repository Structure
```
OCNEI/
│
├── main.m                # Primary entry point of the demo version
├── functions/            # Core MATLAB functions implementing OCNEI components
├── datasets/             # Raw network datasets utilized in the experiments
├── results/              # Automatically generated output files
└── README.md             # Documentation file
```

---

## 5. Notes on Reproducibility
- This release provides a demonstration version intended to facilitate verification of the core experimental results.  
- The complete source code and extended datasets will be available upon reasonable request after publication, in accordance with institutional data policies.  
- For transparency, the pseudocode of the proposed OCNEI method has been added to the Methodology section of the paper.  

---
# OCNEI
OCNEI
