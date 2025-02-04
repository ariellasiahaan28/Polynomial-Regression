# Polynomial-Regression
This project implements a 1D Polynomial Regression Model and applies it to multiple datasets. The regression model is formulated as a weighted polynomial function with a bias term, and parameters are optimized using Least Squares (LS) and Regularized Least Squares (L2-regularization).

The implementation includes a Python script (poly_reg.py) containing the PolynomialRegression class with methods for model fitting, prediction, and error evaluation. The main tasks involve:

- Implementing LS and L2-regularized LS solutions.
- Evaluating the impact of dataset size, polynomial order, and regularization strength on model performance.
- Computing and visualizing training and test errors using Mean Squared Error (MSE).


Experiments are conducted in the Jupyter notebook (poly_notebook.ipynb), analyzing:
1. The effect of dataset size on error metrics.
2. The impact of increasing polynomial order on overfitting and underfitting.
3. The role of regularization in improving generalization.
4. Final results, including visualizations and analysis, are compiled in poly_results.pdf.
