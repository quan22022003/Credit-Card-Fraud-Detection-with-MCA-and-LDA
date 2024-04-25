# Credit Card Fraud Detection Project

## Overview
This project focuses on developing robust credit card fraud detection models using advanced statistical methods, specifically Multiple Correspondence Analysis (MCA) and Linear Discriminant Analysis (LDA). Our goal is to enhance the detection accuracy of fraudulent transactions, thereby reducing financial losses and preserving consumer trust.

## Contents

- **card_transdata.csv** - Dataset used for training and analysis, containing detailed transactions labeled for fraud.
- **Project.pdf** - Detailed project report including the research question, methodologies, data analysis, and conclusions.
- **Project.Rmd** - R Markdown file containing the analytical code and documentation.
- **resources/**

## Research and Methodology

The project applies a combination of MCA and LDA to a dataset of credit card transactions. The objective is to identify existing fraudulent activities and predict potential fraud scenarios. Various statistical methods, including Pearson’s correlation coefficient and Chi-square tests, are employed to understand dependencies and multicollinearity within the data.

### Key Points:

- **Data Preprocessing**: The dataset, sourced from Kaggle, includes 7 explanatory variables across 1,000,000 transactions, reduced to 3,000 rows for model training and validation .
- **Univariate and Multivariate Analysis**: In-depth analysis including distribution visualizations and multicollinearity checks via scatter plots and Pearson’s correlation coefficients .
- **Model Training and Evaluation**: Detailed explanation of model training, including the handling of imbalances in the dataset and assumptions about data normality. The models' effectiveness is evaluated based on precision, recall, and F1 scores, with a focus on minimizing false positives due to the high cost associated with fraudulent transactions .

## Installation and Usage

1. Install necessary R packages:
   ```R
   install.packages("ggplot2")
   install.packages("MASS")  # For LDA
   ```
2. Run the `Project.Rmd` in RStudio to replicate the analysis.

## Results and Conclusions

The analysis achieved high specificity and precision, indicating strong performance in identifying non-fraudulent transactions. While the model excels at minimizing false positives, the recall for fraudulent transactions indicates room for improvement. Future work will explore more sophisticated feature engineering and the integration of additional data sources to enhance model learning and prediction accuracy .

## How to Contribute

Contributions to the project are welcome! Please fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
