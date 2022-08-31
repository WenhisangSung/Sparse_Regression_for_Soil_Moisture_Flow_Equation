# Sparse Regression for Soil Moisture Flow Equation


Codes for Data-driven discovery of soil moisture flow governing equation: A sparse regression framework. Water Resources Research, 58, e2022WR031926. https://doi.org/10.1029/2022WR031926

## Requirements

- Python 3.6.13
- Tensorflow 1.14
- Matplotlib
- Numpy
- Pandas

## Datasets

See Data folder, details can be found in journal article.

## Codes

Use step1.py (finite methods for clean data and automatic differentiation methods for noisy data) to generate a candidate library, then input into step2 sparse regression.

## Citation

```
Song, W., Shi, L., Wang, L., Wang, Y., & Hu, X. (2022). Data-driven discovery of soil moisture flow governing equation: A sparse regression framework. Water Resources Research, 58, e2022WR031926. https://doi.org/10.1029/2022WR031926
```