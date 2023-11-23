# Deep Neural Networks for Portfolio Selection

## Overview 🌐
This project replicates and evaluates the Deep Neural Network (DNN) methodology introduced by Da & Jiang (2022) for multi-period portfolio optimization, considering the serial dependence of returns. The initial results highlight the need for further robustness checks to rigorously validate any performance advantages.

## Background 📚
Portfolio selection poses significant challenges due to high-dimensional covariance matrices, the need for flexible modeling of return dynamics, and various investment constraints. Deep learning offers promising solutions but is susceptible to overfitting. This project explores the application of a DNN architecture on simulated data to test its efficacy in this context.

## Implementation 💡
- **Deep Neural Network Model**:
  - Architecture: Feedforward DNN with 2 hidden layers.
  - Activation Function: Tanh.
  - Optimization: Batch ADAM.
- **Testing Scenarios**:
  - Asset return processes: AR(1) and CCC-GARCH(1,1).
  - Analysis Focus: Convergence, wealth trajectories, model dynamics, and capital allocation curves.

## Results 📊
- The DNN demonstrates reasonable convergence and sensible model dynamics.
- Challenges Identified:
  - Multi-period models underperform compared to single-period models.
  - Overfitting likely contributes to observed discrepancies.

## Discussion 🔍
Further refinement and rigorous evaluation are needed in areas including:
- Reassessment of the single-period model formulation.
- Enhancing out-of-sample evaluation methods.
- Reducing model complexity to mitigate overfitting.
- Reconciling performance differences.
- Ensuring the deep learning approach efficiently addresses portfolio optimization challenges.

## Next Steps 🚀
- Re-confirm single-period performance.
- Implement a rigorous validation suite.
- Experiment with adjustments to the DNN model.
- Investigate and address performance gaps.
- Detail techniques for data processing and analysis.


*This README is part of a graduate course project for the Department of Applied Mathematics and Statistics at Stony Brook University.*

