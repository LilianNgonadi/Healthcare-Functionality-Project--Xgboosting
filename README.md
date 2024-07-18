# Healthcare-Functionality-Project--Xgboosting

![output Photo](output.png "Nigerian Functionality Map")

## Author: Lilian Ngonadi

## :memo: Description

- This project addresses a classification machine learning challenge focused on utilizing the GRID3 NGA Health Facilities dataset. The objective is to categorize health facilities across Nigeria based on operational status, utilizing the **XGBOOST algorithm** to enhance prediction accuracy.
- By integrating this rich geospatial dataset, the project aims to improve resource allocation and planning for healthcare services, targeting facilities based on their functionality and operational needs.

## :file_folder: Code
- [Credit Card Lead Prediction.ipynb](https://github.com/AbhishekGit-hash/Credit-Card-Lead-Prediction/blob/master/Credit%20Card%20Lead%20Prediction.ipynb)
- [Credit Card Lead Prediction.ipynb (nbviewer)](https://nbviewer.org/github/AbhishekGit-hash/Credit-Card-Lead-Prediction/blob/master/Credit%20Card%20Lead%20Prediction.ipynb) (_Click on this link if the notebook doesnot load on Github._)

## :hourglass: Dataset

The dataset train.csv is employed for training a model to classify health facilities in Nigeria based on operational status using the GRID3 NGA Health Facilities dataset. It comprises records of 245,725 health facilities, each characterized by selected attributes:
- **Latitude** : Geographical latitude of the facility.
- **Longitude** : Geographical longitude of the facility.
- **Wardname** : Name of the ward where the facility is located.
- **Lganame** : Local Government Area of the facility.
- **Statename** : State in which the facility is located.
- **Category** : Category of the health facility (e.g., hospital, clinic).
- **Ownership** : Whether the facility is government-owned, private, or other.)
- **Type** : Type of health facility (e.g., general hospital, specialist clinic)
- **Func_Stats** : Functional status of the facility indicating if it is operational, not operational, partially operational, or status unknown (encoded as functional, non-functional, partially functional, unknown).

- This dataset provides a comprehensive view of the health facilities' geographical distribution and operational characteristics, facilitating targeted interventions and resource allocation.

## Exploratory Data Analysis (EDA)
* To understand the dataset an exploratory data analysis was carried out to visualize the various features of [GRID3 NGA Health Facilities dataset:](https://data.grid3.org/datasets/1b358b47e41244cbaaccb640d9a4bfc9_0/about)

### Visualize Numerical Feature Distribution

* The dataset is highly imbalanced, oversampling will be needed to create synthetic data to balance the clases.

* Implement Supervised Learning Classifiers. Five classifiers were implemented and the best performing had its hyperparameters tuned.  Random Forest was the best performing and the others were Logistic Regression, Logistic Regression with SMOTE oversampling, Decision Tree with SMOTE oversampling, and XGBoost with SMOTE oversampling.
  
