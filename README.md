Hi ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif)My name is Ghazy Rafif Agustian
============================================================================================================================================

* 🌍  I'm based in Jakarta
* ✉️  You can contact me at [ghazyyrafif@gmail.com](mailto:ghazyyrafif@gmail.com)
* 🧠  I'm learning Machine Learning & Deep Learning
* 🤝  I'm open to collaborating on I’m looking to collaborate on open-source projects that contribute to machine learning research or build impactful data products.
* ⚡  When I'm not coding, you can find me gaming or reading about cutting-edge AI research.

### Socials

<p align="left"> <a href="https://discord.com/users/ghzyrff" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/discord-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/discord.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/discord.svg" width="32" height="32" /> </picture> </a> <a href="https://www.github.com/ghazyrafif" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /> </picture> </a> <a href="http://www.instagram.com/ghazyrff" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/instagram.svg" width="32" height="32" /> </picture> </a> <a href="https://www.linkedin.com/in/ghazyrafif" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" /> </picture> </a> <a href="http://www.medium.com/ghazyyrafif" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/medium-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/medium.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/medium.svg" width="32" height="32" /> </picture> </a> <a href="https://www.youtube.com/@ghazyyrafif" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/youtube-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/youtube.svg" /> <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/youtube.svg" width="32" height="32" /> </picture> </a></p>

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

