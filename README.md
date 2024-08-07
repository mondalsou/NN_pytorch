# Objective

Getting familiar with PyTorch modeling, checking model convergence, data balancing (epoch-wise), PyTorch data sampler, overfitting/underfitting, and fully connected neural networks.

# Steps

1. **Start a Jupyter notebook**
2. **Repeat exercise 1:** Instead of doing classification using Random Forest, perform classification using a fully connected neural network made with PyTorch.
3. **Repeat exercise 2:** Instead of doing regression using Random Forest, perform regression using a fully connected neural network made with PyTorch.
4. **Implement epoch-wise train loss and validation loss plots to check convergence.**
5. **Try another data balancing technique:** Perform epoch-wise random undersampling to balance classes and enforce equal instances of each class per batch.
6. **Start by making the model overfit on the training dataset:** Add a lot of parameters and no regularization. Then address the overfitting problem by:
   - Adding L1 and L2 loss terms in PyTorch loss calculation.
   - Adding dropout layers in the model.
   - Implementing early stopping (based on validation performance).
   - Reducing model parameters.
