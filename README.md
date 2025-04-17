# Team-Fortran_FidelFolio

This repository contains a comprehensive suite of deep learning and statistical models implemented for time series forecasting. The models have been applied to various targets, with outputs shared in corresponding Excel prediction files.

## Repository Structure

- `data_preprocessing.ipynb`: Preprocessing script to clean and prepare time series data for modeling.
- `CNN_LSTM.ipynb`: Implementation of a hybrid CNN-LSTM model for capturing both spatial and temporal dependencies.
- `Transformer.ipynb`: Transformer-based model tailored for sequential prediction.
- `mlpff1.ipynb`, `mlpff2.ipynb`, `mlpff2.ipynb`: Multi-Layer Perceptron Feed-Forward models for baseline comparisons or ensemble approaches.
- `sarimaxff.ipynb`: Statistical SARIMAX model with feature fusion for traditional forecasting comparison.
- `predictions_Target1.xlsx`, `predictions_Target2.xlsx`, `predictions_Target3.xlsx`: Model outputs for three different forecasting targets.
- `README.md`: This file.

## Models Implemented

1. **CNN-LSTM**  
   Combines convolutional layers to extract features with LSTM layers to learn long-term dependencies.

2. **Transformer**  
   Utilizes self-attention mechanisms for long-sequence modeling without relying on recurrence.

3. **MLP-FF (mlpff1, mlpff2)**  
   Dense feed-forward networks trained on flattened time series inputs.

4. **SARIMAX-FF**  
   Traditional seasonal autoregressive model with exogenous variables.

## Output Files

The predictions for each target variable are stored in separate Excel files:
- `predictions_Target1.xlsx`
- `predictions_Target2.xlsx`
- `predictions_Target3.xlsx`

Each file contains the predicted values for the corresponding target from different models.

## 🛠 Requirements

Make sure to install the following packages (via `pip` or `conda`):

```bash
numpy
pandas
matplotlib
scikit-learn
tensorflow
statsmodels
openpyxl
