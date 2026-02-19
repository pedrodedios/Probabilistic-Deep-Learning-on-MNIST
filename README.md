# Probabilistic-Deep-Learning-on-MNIST

This project explores **uncertainty quantification in deep learning** using the :contentReference[oaicite:0]{index=0} dataset as a controlled experimental setting.

The repository demonstrates how **Bayesian deep learning techniques**, particularly **Monte-Carlo Dropout**, can be used to move beyond standard point predictions and instead produce:

- **Predictive probabilities**
- **Model uncertainty estimates**
- **Confidence–accuracy relationships**
- **Robustness analysis under input perturbations**

Starting from a high-accuracy deterministic CNN baseline (~99% test accuracy), the project introduces **stochastic forward passes** to approximate Bayesian inference and measure **epistemic uncertainty**.  
Results show that **incorrect predictions correlate with higher uncertainty**, and that uncertainty increases under **distribution shifts** such as image rotations.

Overall, this work illustrates how **lightweight probabilistic methods** can make deep learning models more **interpretable, reliable, and suitable for safety-critical applications**.
