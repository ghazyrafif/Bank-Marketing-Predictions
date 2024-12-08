# Bank Marketing Prediction

This repository contains a data science project focused on predicting customer subscriptions for a bank's marketing campaign using machine learning models. The project aims to improve campaign efficiency by identifying high-potential customers.

## Table of Contents
- [Background](#background)
- [Goals and Objectives](#goals-and-objectives)
- [Dataset Overview](#dataset-overview)
- [Modeling Approach](#modeling-approach)
- [Key Insights](#key-insights)
- [How to Use](#how-to-use)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)

---

## Background
The dataset comes from a bank's marketing campaign promoting its time deposit products. The campaign faced challenges such as:
- Low conversion rates.
- High campaign costs.
- Lack of effective customer segmentation.

This project uses machine learning to predict the likelihood of customer subscriptions, thereby improving campaign effectiveness.

---

## Goals and Objectives
### Goals
- Increase the success rate of marketing campaigns using predictive analytics.
- Reduce campaign costs by focusing on high-potential customers.

### Objectives
- Develop predictive models to identify customers likely to subscribe.
- Analyze key factors influencing customer decisions.
- Provide actionable recommendations for future campaigns.

---

## Dataset Overview
- **Source**: Marketing campaign data.
- **Size**: 41,118 rows and 20 features.
- **Target Variable**: `y` (Subscription status: Yes/No).
- **Features**:
  - Client Information: Age, Job, Marital Status, Education, etc.
  - Contact Details: Month, Day of Week, etc.
  - Campaign Information: Previous outcomes, number of contacts, etc.
  - Socio-economic Indicators: Employment variation rate, consumer confidence index, etc.

---

## Modeling Approach
### Models Tested
- Random Forest
- Gradient Boosting
- LightGBM
- XGBoost

### Best Model
- **LightGBM with Hyperparameter Tuning**
  - Accuracy: 89.63%
  - ROC-AUC: 79.58%
  - Precision: 70.24%
  - Recall: 21%
  - F1-Score: 32%

### Key Factors Influencing Subscription
- Socio-economic indicators.
- Timing of the campaign (month, contact frequency).
- Historical campaign outcomes.

---

## Key Insights
1. **Optimal Campaign Timing**:
   - High conversion rates observed in March, September, and December.
   - Focus campaigns on stable financial periods (e.g., low Euribor rates).

2. **Customer Segmentation**:
   - Prioritize students and retired individuals, as these groups have higher conversion rates.
   - Avoid contacting customers excessively (more than 10 times).

3. **Strategic Recommendations**:
   - Run campaigns during high consumer confidence periods.
   - Use past campaign outcomes for segmentation.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<username>/Bank-Marketing-Prediction.git

