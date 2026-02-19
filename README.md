# Probabilistic-Deep-Learning-on-MNIST

This project explores **uncertainty quantification in deep learning** coded in **PyTorch** and using the MNIST dataset as a controlled experimental setting.

Instead of producing only a single prediction, the model is extended with **Monte-Carlo Dropout** to estimate:

- **Prediction confidence**
- **Epistemic (model) uncertainty**
- **Confidence vs. accuracy behavior**
- **Robustness under distribution shift** (e.g., rotated digits)

Key highlights:

- Built a **Bayesian CNN** in PyTorch with stochastic inference
- Achieved **~99% classification accuracy** while quantifying uncertainty
- Showed that **misclassified samples exhibit higher entropy and mutual information**
- Provided **visualizations and metrics** useful for real-world reliability analysis

This repository is designed to showcase practical skills in:

- **Probabilistic Deep Learning**
- **Uncertainty Quantification**
- **PyTorch model development**
- **Experimental evaluation and visualization**

The goal is to illustrate how lightweight Bayesian techniques can make neural networks **more trustworthy, interpretable, and production-ready**, especially in **risk-sensitive applications**.
