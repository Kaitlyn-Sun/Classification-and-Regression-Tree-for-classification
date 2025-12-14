# Classification and Regression Tree for Classification

This project implements a Classification and Regression Tree (CART) algorithm
from scratch in Python and compares its behavior with
`sklearn.tree.DecisionTreeClassifier`.

The goal of this project is to evaluate whether a custom implementation can
successfully reproduce the predictions and decision behavior of scikit-learn
under identical experimental settings.

---

## Project Overview

We evaluate our CART implementation on two public benchmark datasets:

- **Breast Cancer dataset**
- **Wine dataset**

For each dataset, our implementation is compared with scikit-learn’s
DecisionTreeClassifier using the same hyperparameters and identical train/test
splits. The comparison is conducted across multiple evaluation perspectives,
including prediction agreement, accuracy, confusion matrices, and class-wise
precision and recall.

---

## Prerequisites

This project assumes basic familiarity with Python and standard scientific
computing libraries.

Before running the experiments, please ensure that your Python environment
matches the required versions listed below.

---

## Environment Setup

The code was developed and tested using the following environment:

- **Python**: 3.10
- **NumPy**: 2.3.2
- **Matplotlib**: 3.10.5
- **scikit-learn**: 1.7.1

To ensure reproducibility, we provide a Conda environment configuration file.

```bash
conda env create -f environment.yml
conda activate cart-project
```

Once the environment is activated, you should be able to run all experiments
without additional package installation.

---

## Running the Experiments

All experiments are implemented in a single Jupyter Notebook (CART.ipynb) located in the src/ directory.

The experimental results can be reproduced by executing all cells in the notebook.

---

## Data

This project uses public benchmark datasets provided by scikit-learn.

- **Iris dataset**: loaded via `sklearn.datasets.load_breast_cancer`
- **Wine dataset**: loaded via `sklearn.datasets.load_wine`

No external data files are required.

---

## Authors

## Authors

- Lihao Xu (lihao_xu@brown.edu)
- Zheyu Shi (zheyu_shi@brown.edu)
- Haowen Qin (haowen_qin@brown.edu)
- Yaqi Sun (yaqi_sun@brown.edu)


---

## License

This project is licensed under the MIT License.
