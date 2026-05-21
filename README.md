# Fidelity of Quantum Circuits in NISQ Systems via Supervised Regression

This repository contains the source code and dataset used in the paper **"Fidelity of quantum circuits in NISQ Systems estimated via supervised regression"**, presented at the Brazilian Congress on Quantum Science and Technology (CBCTQ 2026).

## Abstract
Estimating quantum circuit fidelity prior to hardware execution is essential for guiding circuit design without resorting to costly procedures such as quantum tomography. This work evaluates five supervised regression models on a dataset of NISQ-era operational metrics, demonstrating that quantum gate fidelity is learnable from operational variables with $R^{2} > 0.948$.

## Project Structure
* `/data`: Contains the `QuantumGateBench.csv` dataset.
* `/notebooks`: Contains the `models.ipynb` file with the implementation of the regression models.
* `/requirements.txt`: List of dependencies required to run the analysis.

## Machine Learning Models
The following models were implemented and compared using 5-fold cross-validation:
* Linear Regression
* Random Forest
* XGBoost
* Multi-Layer Perceptron (MLP)
* Support Vector Regression (SVR)
