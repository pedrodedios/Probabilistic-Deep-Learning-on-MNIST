# Probabilistic-Deep-Learning-on-MNIST


<p align="center">
  <img src="MNIST.png" width="450">
</p>



This project explores **uncertainty quantification in deep learning** coded in **PyTorch** and using the MNIST dataset as a controlled experimental setting. 
The goal of this notebook is to illustrate how lightweight Bayesian techniques can make neural networks **more trustworthy, interpretable, and production-ready**, especially in **risk-sensitive applications**.

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

