# Marathon Training: Running Session Decision Support System

Bayesian decision support system for personalised marathon training session recommendations.

## Overview
This project develops a Bayesian Network–based decision support system (DSS) to recommend the most appropriate running session type for an athlete during a marathon training cycle. The system incorporates factors such as injury status, training phase, physical condition, and previous session effort to personalise training recommendations.

## Contents
- `DSS_Bayesian_Network.ipynb` — Jupyter notebook for network design, implementation, and querying
- `DSS Bayesian Network - Report.pdf` — Report detailing design, logic, and use cases

## Key Features
- Bayesian Network constructed using `pgmpy`
- Training phases modelled: Base, Build, Peak, Taper
- Session recommendations: Long Run, Easy Run, Speed Session, Rest Day
- Supports probabilistic reasoning with partial or full evidence
- Queries return interpretable recommendations and insights

## Technologies Used
- Python
  - `pgmpy` for probabilistic modelling
  - `pandas` for data handling
  - `matplotlib` and `networkx` for visualisation

## Author
Richard Smith

