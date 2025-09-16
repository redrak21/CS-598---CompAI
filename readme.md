# EECS 595 Homework 1 - Text Classification

This repository contains implementations of logistic regression for text classification using both NumPy and PyTorch.

## Project Structure

### NumPy Implementaton
- **Main file**: `mainNumpy.py`
- **Implementation**: `NumpyImp.py`
- **Run with**: `python mainNumpy.py`

### PyTorch Implementation
- **Main file**: `main.py`
- **Implementation**: `PytorchImp.py`
- **Run with**: `python main.py`

### Required Files
Both implementations depend on the following files:

#### Utility Files
- `TDM.py` - Term Document Matrix creation and tokenization functions
- `utils.py` - Label loading and vocabulary creation utilities

#### Implementation Files
- `NumpyImp.py` - NumPy-based logistic regression implementation
- `PytorchImp.py` - PyTorch-based logistic regression implementation

### Python Dependencies
- `numpy`
- `pandas`(not for main inplementatin)
- `scipy`
- `torch` (for PyTorch implementation)
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Usage

### Running NumPy Implementation
```bash
python mainNumpy.py
```

### Running PyTorch Implementation
```bash
python main.py
```
