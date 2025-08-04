# The Generalisation of Fairness: A Study of Bias-Mitigated AI Models

This repository contains the code and resources for my MSc Artificial Intelligence dissertation project at Birmingham City University. 

## Abstract

This research investigates whether applying bias-mitigation techniques to a clinical prediction model enhances its fairness and robustness when evaluated on a chronologically distinct and more diverse patient subset. Using the MIMIC-IV dataset, a baseline deep learning model and a fairness-mitigated model are trained on historical data (2008-2016) and comparatively evaluated on contemporary data (2017-2022) to assess the generalisability of the fairness intervention.

## Setup and Installation

To replicate this project's environment, please follow these steps.

1.  **Manage Python Version:** This project uses a specific version of Python, managed by `pyenv`. Set the local version by running:
    ```bash
    pyenv local 3.11.9
    ```

2.  **Create and Activate Virtual Environment:** Create a virtual environment and activate it.
    ```powershell
    # Create the venv
    python -m venv .venv

    # Activate the venv
    .\.venv\Scripts\Activate.ps1
    ```

3.  **Install Dependencies:** All required packages are listed in the `requirements.txt` file. Install them using pip.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

The primary analysis and model development are contained within the Jupyter Notebooks located in the `/Code` directory. Once the environment is set up and the packages are installed, you can start a JupyterLab session to run the notebooks:
```bash
jupyter lab
```

## Citing this Work

If you use this project in your research, please consider citing it.