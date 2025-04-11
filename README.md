# 🔗 Linear-Modularity-Node-Embeddings

Welcome to the official repository for **Linear-Modularity-Node-Embeddings** — a fast and efficient semi-supervised node embedding method that blends **linear modularity optimization**, **label propagation**, and an **attention mechanism** to generate embeddings that are both **structurally meaningful** and **discriminatively powerful**.

---

## 🚀 Overview

This repository includes everything you need to reproduce the experiments from our study conducted on **five benchmark graph datasets**.

Our method ensures that the resulting node embeddings:
- Preserve **graph structure** through modularity optimization
- Leverage **node labels** with label propagation
- Enhance **feature focus** using attention mechanisms

---

## 📁 Repository Contents

- 📓 **Benchmarking Notebooks**  
  A collection of Jupyter notebooks used to evaluate the method across five datasets:  
  `cora`, `citeseer`, `photo`, `pubmed`, and `wikics`.  
  You’ll find these inside the `Benchmarking Notebooks/` directory.

- 🛠 **Anaconda Environment File**  
  The file `modularity_node_embedding.yaml` contains all required dependencies to set up your environment.

---

## ⚙️ How to Run

1. **Create and Activate the Environment**
    ```bash
    conda env create -f modularity_node_embedding.yaml
    conda activate modularity_node_embedding
    ```

2. **Set Up Result Directory**  
   Inside the working directory, create a folder named `<datasetname>_analysis_results`, replacing `<datasetname>` with one of:
   - `cora`
   - `citeseer`
   - `photo`
   - `pubmed`
   - `wikics`

   Example:
    ```bash
    mkdir cora_analysis_results
    ```

3. **Launch JupyterLab**  
   Ensure the results folder and the corresponding notebook are in the same directory, then run:
    ```bash
    jupyter lab
    ```

4. **Run the Notebook**  
   Open the notebook for your dataset and execute all cells to reproduce the results.

---
