# Bootstrap Sampling & Bagging on Moon Dataset

This repository contains a Jupyter notebook that applies **bootstrap sampling** and **bagging (bootstrap aggregating)** using a simple **Keras neural network** on a binary classification problem (the “moon” dataset).

The main goals of this assignment are:

- Generate multiple bootstrap samples from a training set  
- Train a neural network classifier on each bootstrap sample  
- Evaluate the **error per bootstrap sample**  
- Build an **ensemble (bagging)** of neural networks and study how the error changes as the ensemble size increases  

---

## Repository Structure

- `Ensemble.ipynb` – Main notebook with all the code and analysis  
- `moonDataset.csv` – Dataset used in the notebook (2D features + binary label)  
- `README.md` – This file  

> Make sure `moonDataset.csv` is in the same directory as the notebook when you run it.

---

## Requirements

This project uses Python 3 and the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `tensorflow` (Keras)
- `scikit-learn`
- `tqdm`
- `jupyter` (to run the notebook)

You can install the dependencies with:

```bash
pip install pandas numpy matplotlib tensorflow scikit-learn tqdm jupyter
