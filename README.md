# SVM Parameter Optimization

This project optimizes hyperparameters for a Support Vector Machine (SVM) classifier on the UCI Letter Recognition dataset. It uses random search with early stopping to tune parameters like Kernel, Nu, and Gamma across multiple samples.

## Dependencies
- python
- numpy
- pandas
- scikit-learn
- matplotlib

## Usage
1. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```
2. Run `EAI_Convergence_Assignment_.ipynb`.

## Outputs
- **`svm_results_fast/optimized_svm_summary.csv`**: Summary of best parameters and accuracy.
- **`svm_results_fast/convergence_S*.png`**: Convergence plot of the best run.
