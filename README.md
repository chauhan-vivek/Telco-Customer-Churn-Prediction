Telco Customer Churn Analysis
==============================
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a>
    <img src="readme-assets/intro.png" alt="Logo" width="240" height="240">
  </a>
</div>

Analysis of IBM telco-customer churn.

This project focusses on doing descriptive analysis and creating rich visualization to be presented to stakeholders. IT further creates a simple logistic regression model with statistical significance to classify customers into churn and non-churn groups. The insights generated from this EDA are used to create data driven strategic recommendations to retain customers who are potential candidate to churn in coming month. 

## Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
	├── readme-assets      <- Contains images to be used in README.md
    ├── data
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks for downloading dataset, carrying out EDA and building recommendation system
    │
    ├── reports            <- Generated analysis as PDF.
    │   └── figures        <- Generated graphics and figures to be used in reporting
	├── requirements.txt   <- The requirements file for reproducing the analysis environment, 
								e.g. generated with `pip freeze > requirements.txt`

--------

## Analysis
------------

### EDA

<div align="center">
  <a>
    <img src="readme-assets/univariate_and_bivariate_analysis.PNG" alt="Logo" width="480" height="480">
  </a>
</div>

<div align="center">
  <a>
    <img src="readme-assets/monthly_charges_and_total_charges_tenure_group_attrition.PNG" alt="Logo" width="480" height="480">
  </a>
</div>

<div align="center">
  <a>
    <img src="readme-assets/correlation_churn_nonchurn.PNG" alt="Logo" width="480" height="480">
  </a>
</div>


### Model

<div align="center">
  <a>
    <img src="readme-assets/model_performance.PNG" alt="Logo" width="480" height="480">
  </a>
</div>

Ackowledgements
------------
* [IBM](https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=samples-telco-customer-churn)
--------