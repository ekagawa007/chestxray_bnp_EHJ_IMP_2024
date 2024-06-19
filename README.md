
# Predicting elevated natriuretic peptide in chest radiography

This repository provides the implementation code for models predicting elevated BNP levels.

Kagawa et al. Predicting elevated natriuretic peptide in chest radiography: Emerging utilization gap for artificial intelligence. European Heart Journal – Imaging Methods and Practice 2024 in press

## Model Download
You can download the model file from the following link:
BNP cut-off 200 pg/mL:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12150323.svg)](https://doi.org/10.5281/zenodo.12150323)

BNP cut-off 100 pg/mL:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12145781.svg)](https://doi.org/10.5281/zenodo.12145781)


## Usage

1. Download the model and save it to your local environment.
2. Load the model using the following code.

```python
from tensorflow.keras.models import load_model

# Specify the path to your model
model_path = 'path/to/your/model.h5'
model = load_model(model_path)
