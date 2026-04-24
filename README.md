# Applied Machine Learning Playbook

This repository is a broad, hands-on ML notebook collection designed to showcase practical workflow depth across multiple paradigms:

- supervised learning,
- unsupervised learning,
- deep learning,
- reinforcement learning.

Rather than focusing on one benchmark, it demonstrates reusable modeling patterns across different data modalities and objectives.

## Repository Purpose

The project serves as an experimentation playbook for:

- data preparation templates,
- baseline-to-advanced model progression,
- evaluation and visualization habits,
- cross-domain transfer of ML techniques.

## Notebook Coverage by Domain

### Tabular Supervised Learning

- `Iris.ipynb`
- `Penguins.ipynb`
- `Housing.ipynb`

Focus areas:

- feature inspection,
- train/test workflows,
- baseline estimator comparisons.

### Unsupervised Learning / Segmentation

- `Mall_Customers_Clustering.ipynb`
- `Wholesale_Customers_Clustering.ipynb`

Focus areas:

- cluster discovery,
- segmentation interpretation,
- unsupervised evaluation heuristics.

### Neural Networks and Computer Vision

- `MNIST_Neural_Network.ipynb`
- `MNIST_Neural_Network_6_Obs.ipynb`
- `CNN_w_MNIST.ipynb`

Focus areas:

- feed-forward vs convolutional architectures,
- image classification training loops,
- comparative learning behavior.

### Reinforcement Learning

- `Reinforcement_Learning.ipynb`

Focus areas:

- policy/value update concepts,
- reward-driven optimization flow,
- iterative agent behavior.

## Tech Stack

- Python
- pandas, NumPy
- scikit-learn
- TensorFlow / PyTorch (notebook dependent)
- matplotlib, seaborn
- Jupyter

## Environment Setup

```bash
python -m venv venv
venv\Scripts\activate
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow torch jupyter
jupyter lab
```

## Recommended Learning Path

1. Start with tabular notebooks to establish baseline workflow habits.
2. Move to clustering notebooks for unsupervised reasoning.
3. Continue to MNIST neural-network notebooks for deep learning progression.
4. Finish with reinforcement learning to cover sequential decision making.

## How to Evaluate This Repository

For recruiters and reviewers, this repo demonstrates:

- versatility across ML problem families,
- consistent notebook-based experimentation discipline,
- ability to move between theory and implementation quickly.
