# **PPDA**  
Welcome to the official repository for our paper *"PPDA,"* published at **ICONIP 2024**. This repository includes the code and data used in our experiments.  

---

## **Paper**  
Thank you for visiting! You can access the preprint of our paper [here](https://drive.google.com/file/d/1O20RbdPj17C6uOtcnnVUvmHnNXaAUZwc/view?usp=sharing).  

---

## **Highlights**  
Our framework is designed to achieve the following:  
1. **Secure Distance Learning**: Compute pairwise distances without revealing sensitive features.  
2. **Graph Learning**: Utilize secure distance information to construct robust graphs.  
3. **Graph Embedding**: Generate graph embeddings to enable advanced machine learning tasks.  

---

## **Installation**  
pip install -r requirements.txt 

---
## **Results**
To reproduce the results, follow these steps:

**Synthetic Datasets**:
Run PPDA_synthetic_data.ipynb to obtain results for the synthetic datasets:

ER (Erdős–Rényi)
BA (Barabási–Albert)
RGG (Random Geometric Graph)
These results correspond to Table 1, Table 2, and Figures 3 and 4.

**Real Datasets**:
Run PPDA_real_data.ipynb to generate results for the following real-world datasets:

UCI, PANCAN, HAR (Human Activity Recognition), Animal: These results correspond to Tables 4-12 and Figures 5-8.
Ensure that the necessary datasets are available and paths are configured correctly before running the notebooks.

---

## **Citation**  
If you find this repository helpful in your research, please consider citing our work published at ICONIP 2024:  
