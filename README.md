# Machine-Learning-Flare-Dataset

A curated dataset of solar Active Region magnetic field parameters for machine learning–based solar flare forecasting research.

This repository provides pre-processed magnetic field features derived from solar Active Regions, along with a tutorial notebook demonstrating structured exploration and preparation for statistical and machine learning analysis. The dataset is intended to support reproducible flare prediction research and methodological development.

## Scientific Context

Solar flares are explosive releases of magnetic energy in the solar corona, originating from magnetically complex Active Regions (ARs). Reliable forecasting of flares remains a central challenge in space weather research.

Modern flare prediction approaches commonly use:

- Photospheric vector magnetic field measurements

- Derived magnetic complexity metrics

- Time-evolving Active Region parameters

- Supervised machine learning models

This repository provides a structured dataset of AR magnetic parameters processed for direct integration into machine learning pipelines.

The dataset is designed to support:

- Binary flare classification (flare / no-flare)

- Multi-class flare magnitude prediction

- Regression on flare intensity

- Feature selection and importance studies

- Statistical characterisation of AR magnetic complexity

## Usage

### 1. Clone the repository

`git clone https://github.com/DrTomWilliams/Machine-Learning-Flare-Dataset.git`

`cd Machine-Learning-Flare-Dataset`

### 2. Install Requirements
Minimum recommended environment: 

`pip install numpy pandas matplotlib jupyter`

Optional (for ML workflows):

`pip install scikit-learn scipy seaborn`

Python 3.8+ is recommended.

### 3. Launch the Tutorial
`jupyter notebook Tutorial.ipynb`

Run the notebook cells sequentially to explore the dataset.


## Citation

You may cite this repository directly:

Williams, T. Machine-Learning-Flare-Dataset. 
https://github.com/DrTomWilliams/Machine-Learning-Flare-Dataset

For formal publications, please cite:

Williams, Prior, & MacTaggart (2025), *Investigating the Efficacy of Topologically Derived Time Series for Flare Forecasting. I. Data Set Preparation*, *ApJ*, **980**, 102
