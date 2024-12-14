# HowBitterIsTheBeer
This project analyzes a dataset provided by Dennis Sun on Kaggle, containing 6,000 observations and 10 variables, to predict the International Bitterness Units (IBU) of a beer. IBUs quantify the bitterness of beer and are influenced by factors like alcohol content, color, and brewing methods. Using eight variables as potential predictors, this project focuses on exploratory data analysis (EDA), data cleaning, and statistical modeling to determine the best combination of variables for accurately predicting IBU values.

The data cleaning process addressed missing and redundant variables. Variables such as glass, description, available, and name were excluded due to high missing rates, nominal nature, or lack of predictive relevance. Outliers were identified and handled using interquartile range (IQR) bounds, resulting in two cleaned datasets. The first, beerdf_new, contains 5,909 rows with IBU outliers removed, while the second, data_clean, contains 4,944 rows with additional outliers removed for abv, originalGravity, and srm. Key numeric predictors, including abv, originalGravity, and srm, were visualized through histograms and boxplots to assess their distributions and relationships to IBU.
# Installation
1. Clone the repository:
   ```bash
   git clone https
