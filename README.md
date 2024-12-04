# SDWA Analysis: Water Quality and Compliance

<p align="center">
  <img src="" >

  ## Table of contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Future Work](#future-work)
- [Acknowlegements](#acknowledgements)
  
## Overview
This project analyzes public water systems under the Safe Drinking Water Act (SDWA) to identify compliance patterns and categorize water systems based on violations and features.


## Problem Statement
The project focuses on evaluating and segmenting public water systems based on compliance with regulatory standards. These system's compliance is critical to ensuring public health and evironmental protection. The primary research questions are :
- How can public water systems be effectively segmented based on compliance behaviors and violation patterns?
- What key factors contribute to compliance or non-compliance with regulatory standards?
- Can predictive models acurately classify water system's compliance status to improve monitorin and decision-making?

## Solution Strategy
- Segmenting Water Systems
| - Task: Unsupervised clustering using group 3 variables to create profiles of water systems key variables included compliance status, violation counts, and enforcement action categories
| - Outcome: Identified clusters of water systems based on compliance patterns. This segmentation helped classify systems into high-rish, medium-risk, and low-risk categories, enabling focused regulatory interventions.
    
- Identify key Factors
| - Task: Perform feature importance analysis using supervised machine learning models (e.g., Logistic Regression, Naive Bayes). Key features like major violations, late compliance actions, and "outstanding performer" stuat were analyzed.
| - Outcome: Determined which facotrs have the greatest impact on compliance behavior, allowing stakeholders to prioritize areas for improvement.
    
## Features
- Clustering public water systems for compliance segmentation.
- Analyzing violation trends and feature contributions.
- Dashboard integration with Power BI for interactive insights.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/SDWA-Analysis.git


## Visualizations
Clustering Results

<p align="center"> <img src="results/cluster_visualizations.png" alt="Clustering Results" width="70%"> </p>

Compliance Trends

<p align="center"> <img src="results/cluster_visualizations.png" alt="Clustering Results" width="70%"> </p>

## Future Work
Incorportae real-time monitoring using MLOps principles.
Extend to other environemental compliance datasets

# Acknowledgments
- Data sourced:
    - U.S. Environmental Protection Agency (EPA) [SDWA database](https://echo.epa.gov/tools/data-downloads#drinkingwater)
- Tools Used:
    - Jupyter Notebook, Apache Spark and Python (Pyspark), Power BI for visualization
- Support:
    - This project was developed as part of a capstone course in Datascience at UMBC
