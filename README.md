# Deep Neural Networks for Portfolio Selection 📊

This project replicates and evaluates the Deep Neural Network (DNN) methodology introduced by Tsang K. H. and Wong H. Y. in their 2020 paper "Deep-learning solution to portfolio selection with serially dependent returns". We focus on multi-period portfolio optimization in the context of serial return dependence. The initial findings highlight the importance of additional robustness checks for validating performance benefits. 🚀

## Background 🌐

Portfolio selection is a complex challenge, compounded by issues like:

- High-dimensional covariance matrices 
- Need for flexible modeling of return dynamics 
- Various investment constraints 

Deep learning offers promising solutions, but it also brings concerns about potential overfitting. This project tests a DNN architecture against simulated data to explore these challenges. 💡

## Implementation 🛠️

Our implementation features:

- A feedforward DNN model with 2 hidden layers and Tanh activation 
- Batch ADAM optimization for efficient training 
- Testing under AR(1) processes and CCC-GARCH(1,1) dynamics 

The focus is on convergence, wealth trajectories, model dynamics, and capital allocation curves. 

## Results 📋

The DNN model shows:

- Reasonable convergence 
- Sensible model dynamics 
- However, multi-period optimization underperforms single-period models, likely due to overfitting 

## Discussion 💬

Key areas for further exploration include:

- Refining single-period optimization methods 
- Implementing rigorous out-of-sample evaluations 
- Reducing model complexity to mitigate overfitting risks 
- Addressing performance discrepancies for a clearer understanding 

Our goal is to validate deep learning's efficiency in portfolio optimization through more robust methodologies. 

## Next Steps 🚶‍♂️

Moving forward, we plan to:

- Re-confirm single-period performance metrics 
- Introduce a comprehensive validation suite 
- Experiment with model adjustments for better performance 
- Investigate and understand performance gaps 
- Elaborate on our data processing techniques for transparency 






