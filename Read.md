# EDA with Python

This repository is about **world population** — we will explore, clean, and then visualize and present the data using the **Pandas** library.

## Setup Virtual Environment

```bash
# Create a new virtual environment
python -m venv .venv

# Activate the virtual environment on Windows using Git Bash
source .venv/Scripts/activate
```

## Required Libraries

```
pandas
numpy
matplotlib
seaborn
jupyter
openpyxl
ipykernel
```

## Install Required Packages

```bash
# Install all libraries from requirements.txt
pip install -r requirements.txt
```

## Register Kernel with Jupyter

```bash
python -m ipykernel install --user --name=.venv
```
## Create Notebook File

```bash
mkdir scripts
cd scripts
touch world_population_EDA.ipynb
```

## Open Jupyter Notebook

```bash
jupyter notebook
```

## Deactivate Environment When Done

```bash
deactivate
```