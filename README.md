# Deep Neural Networks for Portfolio Selection 📊

## Original Paper Summary 📝

* **Title**: "Deep-learning solution to portfolio selection with serially dependent returns"
* **Authors**: Tsang K. H. and Wong H. Y.
* **Published**: 2020
* **Key Insights**:
  - Proposes a novel deep learning approach for multi-period portfolio optimization.
  - Addresses the challenge of serial return dependence in financial markets.
  - Offers a methodological framework for incorporating deep neural networks in portfolio selection.

## Overview 🌐

This project replicates and evaluates Tsang and Wong's 2020 methodology for multi-period portfolio optimization, considering serial return dependence. Our initial results highlight the need for further robustness checks to validate performance advantages.

## Background and Challenges 🧩

Portfolio selection is complex due to:
- High-dimensional covariance matrices.
- Flexible modeling of return dynamics.
- Various investment constraints.
Deep learning offers potential solutions but faces challenges like overfitting. Our project tests a DNN architecture against simulated data.

## Implementation Details 🛠️

Our implementation includes:
- A feedforward DNN model with 2 hidden layers and Tanh activation.
- Batch ADAM optimization.
- Tests under AR(1) processes and CCC-GARCH(1,1) dynamics.
Focus areas include convergence, wealth trajectories, model dynamics, and capital allocation.

## Results and Observations 📋

The DNN model shows:
- Reasonable convergence.
- Sensible model dynamics.
- Multi-period optimization underperforms single-period models, likely due to overfitting.

## Discussion and Future Directions 💡

Areas for further exploration:
- Refining single-period optimization methods.
- Rigorous out-of-sample evaluations.
- Reducing model complexity to mitigate overfitting.
- Addressing performance discrepancies for clearer understanding.

## Next Steps 🚀

Our future plans involve:
- Re-confirming single-period performance.
- Introducing a comprehensive validation suite.
- Model adjustments for better performance.
- Investigating performance gaps.
- Elaborating on data processing techniques.
