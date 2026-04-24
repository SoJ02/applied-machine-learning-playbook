# Applied Machine Learning Playbook

This repository is a multi-domain ML notebook collection showcasing practical experimentation across supervised learning, unsupervised learning, deep learning, and reinforcement learning.

## What is included

- **Clustering:** customer segmentation and pattern discovery
- **Neural networks / CV:** MNIST feed-forward and CNN workflows
- **Reinforcement learning:** policy/value-based learning experiments
- **Tabular modeling:** Iris, Penguins, Housing, and other structured datasets

## Why this repo exists

It acts as a compact playbook of reusable modeling patterns:

- data prep and feature workflows
- model training and evaluation templates
- cross-problem experimentation habits

## How to run

```bash
python -m venv venv
venv\Scripts\activate
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow torch jupyter
jupyter lab
```

Then run notebooks independently based on topic area.

## Recommended viewing order

1. Tabular notebooks (`Iris`, `Penguins`, `Housing`)
2. Clustering notebooks
3. MNIST neural network notebooks
4. Reinforcement learning notebook
