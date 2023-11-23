# Deep Learning in Portfolio Optimization 📈

## Introduction 📜
This project is based on the study, "Deep-Learning Solution to Portfolio Selection with Serially-Dependent Returns" by Zhiyi Da and Haochen Jiang. It explores the application of deep learning techniques in addressing complex problems in mathematical finance, specifically focusing on multi-period portfolio optimization under Markov decision processes (MDP).

## Problem Statement 🧩
The project aims to tackle the challenges in portfolio optimization, especially in scenarios with high-dimensional and serially-dependent returns. The primary focus is on leveraging autoregressive (AR) and generalized autoregressive conditional heteroskedasticity (GARCH) models within a deep learning framework.

## Methodology 🔍
- **Deep Learning Approach:** Utilizing feedforward neural networks, the project develops a deep-learning solution to the MDP problem. This involves creating feedback control functions and employing a minimization strategy.
- **Simulation and Analysis:** The methodology is substantiated with practical numerical examples, employing Monte Carlo simulations to test the model's effectiveness in handling high-dimensional data.

## Key Findings and Observations 📊
- The proposed deep learning algorithm demonstrates efficiency and robustness in handling up to 100 dimensions.
- Comparative analysis reveals distinct performance variations between multi-period and single-period models.
- The study offers critical insights into the application of the efficient frontier concept in modern portfolio theory.

## Usage and Implementation 🛠️
To implement and utilize the deep-learning solution for this portfolio selection problem, follow these steps:
1. **Data Generation:** Use Monte-Carlo simulation to generate a large dataset for feeding into the deep-learning model, effectively handling high-dimensional problems.
2. **Model Construction:** 
   - **Environment:** 
     - Operating System: Windows 10
     - Programming Language: Python 3
     - Platform: Google Colab
     - Libraries: Keras & Tensorflow (for constructing DNN in multi-period model), cvxopt (for quadratic programming in single-period model)
   - **Neural Network Setup:** 
     - Activation Function: tanh
     - Subnetwork Layers: L = 2 for each subnetwork
     - Hidden Layer Neurons: Varies in different examples
   - **Training:** 
     - Without GPU acceleration
     - Mini-batch optimization
     - Batch Size: 64
     - Optimizer: ADAM (Kingma and Ba, 2014) with default settings.

## Conclusion and Future Work 🔮
The project underscores the potential and limitations of deep learning in financial portfolio optimization, paving the way for further research and refinement in this area.

## References 📚
1. Bachouch, A., Huré, C., Langrené, N., and Pham, H. (2021). Deep neural networks algorithms for stochastic control problems on finite horizon: Numerical applications. Methodology and Computing in Applied Probability, 24(1):143–178.
2. Ban, G.-Y., El Karoui, N., and Lim, A. E. (2018). Machine learning and portfolio optimization. Management Science, 64(3):1136–1154.
3. Lai, T. L. and Xing, H. (2008). Statistical models and methods for financial markets, volume 831. Springer.
4. Li, D. and Ng, W.-L. (2000). Optimal dynamic portfolio selection: Multiperiod mean-variance formulation. Mathematical Finance, 10(3):387–406.
5. Sirignano, J. A. (2019). Deep learning for limit order books. Quantitative Finance, 19(4):549–570.
6. Tsang, K. H. and Wong, H. Y. (2020). Deep-learning solution to portfolio selection with serially dependent returns. SIAM Journal on Financial Mathematics, 11(2):593–619.
7. Zanger, D. Z. (2018). Convergence of a least-squares Monte Carlo algorithm for American option pricing with dependent sample data. Mathematical Finance, 28(1):447–479.
8. Kingma, D.P., and Ba, J. (2014). ADAM: A Method for Stochastic Optimization.

---

*<small>This README is part of a graduate course project for the Department of Applied Mathematics and Statistics at Stony Brook University.</small>*

