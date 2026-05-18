# About the Project

Welcome to the **regression-with-python** repository! This repository contains lecture examples and experiments on regression, optimization, statistics, and machine learning using Python.
- Provides **a friendly introduction** for new learners.  
- Includes **setup instructions** for your environment.  
- Shows a **clear folder map** so users know where to find notebooks, data, and projects.  
- Gives **usage instructions** to run the notebooks.  

# Repository Structure
```
.
├── data
│   ├── automobileEDA.csv 	# Automobile pricing and feature analysis
│   └── FuelConsumptionCo2.csv  # Fuel consumption and CO₂ emissions
│
├── excercise-regression
│   ├── 1.simple-linear-regression.ipynb
│   ├── 2.mulitple-linear-regression.ipynb
│   ├── 3.logistic-regression.ipynb
│   ├── 4.polynomial_regression.ipynb
│   └── README.md
│
├── lecture-regression
│   ├── 1.simple_linear_regression_basic_lecture.ipynb	# A python script to with the lecture examples 
│   └── 2.linear_regression_trackML.ipynb 		# A python script to simplify the data handling of the TrackML dataset used in  high-energy physics
│
└── README.md
```

## Pre-requisites

Make sure you have **Python 3.x**, **Jupyter Notebook**, and a virtual environment set up. 

```bash
# Build the enviroment
python -m venv installations/python_envs/ml_env

# Activate the environment
source installations/python_envs/ml_env/bin/activate

## Pre-requisits
pip install -r requirements.txt
```
## Run the examples
```bash
# Install your environment as a Jupyter kernel
python -m ipykernel install --user --name=ml_env --display-name "ML env"
## Run jupyter
jupyter notebook
```
---
### Contributing and Contact Information:
We welcome contributions from the community please contact : `ahmed.qamesh@gmail.com` .
