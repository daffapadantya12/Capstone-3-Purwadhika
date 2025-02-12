# Travel Insurance Claim Prediction

## Business Problem & Data Understanding

### Business Problem
A travel insurance company wants to predict which policyholders will submit an insurance claim. This prediction can help the company in:

- **Risk Assessment** – Identifying high-risk customers to adjust pricing strategies or policy conditions.
- **Fraud Detection** – Detecting patterns in suspicious claims.
- **Customer Segmentation** – Understanding which demographics or travel types are more likely to make claims.

### Stakeholders & Problem Importance
- **Insurance Company Executives:** Need to optimize risk management and pricing strategies.
- **Underwriting Team:** Wants to assess the likelihood of claims for individual policyholders.
- **Customer Service & Claims Processing Teams:** Can streamline claim approvals by predicting fraudulent or high-risk claims.
- **Financial Team:** Helps in managing reserves for expected claims.

The goal is to create a classification model that predicts whether a customer will submit a claim (**Claim = 1**) or not (**Claim = 0**). The model's success will be measured using metrics such as:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

## Data Understanding
The dataset contains historical records of policyholders and their insurance claims.

### Features and Description

| Feature | Description |
|---------|-------------|
| **Agency** | The name of the agency that sold the insurance. |
| **Agency Type** | The type of travel insurance agency. |
| **Distribution Channel** | Sales channel used for policy distribution. |
| **Product Name** | Travel insurance product name. |
| **Gender** | Gender of the insured customer. |
| **Duration** | Length of the trip. |
| **Destination** | Travel destination. |
| **Net Sales** | Amount of travel insurance sales. |
| **Commission** | Commission received by the travel agency. |
| **Age** | Age of the insured customer. |
| **Claim (Target Variable)** | Whether the policyholder submitted a claim (1) or not (0). |

## Installation Requirements
To run this notebook, install the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Load the dataset into the notebook.
2. Perform exploratory data analysis (EDA) to understand feature distributions and relationships.
3. Preprocess the data (handle missing values, categorical encoding, scaling, etc.).
4. Train classification models such as Logistic Regression, Decision Trees, or Random Forest.
5. Evaluate model performance using classification metrics.
6. Use the trained model for predicting future claims.

## Data Sources
- The dataset is historical data from a travel insurance company.
- Ensure data privacy and compliance while using sensitive customer information.

## Authors & Contributions
- **Belva Sharafina Maharani** - Data Analysis & Model Development
- [Add additional contributors if any]

## License
This project is for educational and research purposes only.

---
Feel free to modify or expand this README as needed!

