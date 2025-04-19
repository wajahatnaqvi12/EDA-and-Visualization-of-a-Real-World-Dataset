# Titanic Dataset - Exploratory Data Analysis (EDA) and Visualization

## Overview
This repository contains an exploratory data analysis (EDA) and visualization of the famous Titanic dataset. The Titanic dataset contains information about the passengers aboard the RMS Titanic, which sank on its maiden voyage in 1912 after colliding with an iceberg.

The analysis focuses on understanding the factors that influenced passenger survival rates through comprehensive data exploration and visualization techniques.

## Dataset Description
The Titanic dataset contains the following features:

### Passenger Information:
- `PassengerId`: Unique identifier for each passenger
- `Survived`: Survival status (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Passenger name
- `Sex`: Passenger gender
- `Age`: Age in years
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Analysis Contents
The repository includes:

1. **Data Cleaning and Preprocessing**
   - Handling missing values
   - Feature engineering
   - Data type conversions

2. **Exploratory Data Analysis**
   - Univariate analysis of each feature
   - Bivariate analysis against survival rate
   - Correlation analysis between features

3. **Data Visualizations**
   - Distribution plots for numerical features
   - Count plots for categorical features
   - Survival rate analysis by different features
   - Interactive visualizations (if applicable)

4. **Key Insights**
   - Factors strongly correlated with survival
   - Interesting patterns and relationships in the data

## Requirements
To run the analysis, you'll need:
- Python 3.6+
- Jupyter Notebook (or JupyterLab)
- Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly (optional for interactive plots)

## Key Findings
Some notable findings from the analysis include:
- Survival rate was significantly higher for:
  - Women and children
  - Upper-class passengers (Pclass 1)
  - Passengers who embarked at Cherbourg
- Age distribution shows many young adults (20-30 years old)
- Fare distribution is right-skewed, indicating most passengers bought cheaper tickets
- Family size (SibSp + Parch) had a complex relationship with survival

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your suggested improvements.

## License
This project is open-source and available under the [MIT License](LICENSE).

## References
- Original dataset source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- Titanic historical information: [Encyclopedia Titanica](https://www.encyclopedia-titanica.org/)
