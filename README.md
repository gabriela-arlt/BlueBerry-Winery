# Project: Analysis of BlueBerry Winery dataset
## Premise of the project: 
The focus of this project is Python and Statistics core concepts and its applications in Machine Learning.
We work as a "Junior Data Analyst" in the Analytics & Research department of CODE Analytics. BlueBerry Winery's team, a start-up wine maker in Portugal,
has approached our company to help them build a Wine Quality Analytics System to help them determine the quality of the wines produced based on their composition.
## DATA: 
 * provided by Code Academy Berlin
 * the file named winequality-red.csv contains the dataset pertaining to 1599 records of red wine samples
 * the file named winequality-white.csv contains the dataset pertaining to 4898 records of white wine samples
 * the file named winequality.names consists of detailed information and the data dictionary pertaining to the datasets
 * Original data: https://archive.ics.uci.edu/dataset/186/wine+quality

# Part 1 (EDA): 
## Python libraries used: numpy, pandas, matplotlib, seaborn, scipy (stats)
## Steps 1: Experimental physe and exploration of the dataset (reference: final_wine_project.ipynb)
   * I have checked for null and na values
   * Standardized column names
   * Concated both dataset for finding trends and differences
   * Experimented with different plots 

## Step 2 (reference: wine+quality/plots for the presentation.ipynb) 
   * Tested some plots
   * Performed feature enjineering
   * Checked which features affect the wine quality
   * Created plots for comparison of the wine types
   * Performed Hypothesis check (ANOVA test, looking at p-value)
   * Checked for imbalanced data
   * Created more plots for observing the correlation between chemical compunds and wine quality
   * Created Heatmaps
# Part 3: Machine Learning 
## Python libraries used: numpy, pandas, matplotlib, seaborn, scipy, skilearn, SMOTE
## I have created several ML models based on different features and followed different steps
1. File: ML- Quality Label Full Dataset with outliers, oversampling and scaling.ipynb
   * dropped duplicates
   * concated both datasets
   * performed feature enjineering
   * dropped unnecessary columns
   * oversampled with SMOTE
   * tested Random Forest Model
   * tested KNN Model
   * tested Support Vector Machines (SVM)
2. File: wine+quality/ML- Quality Label Full Dataset without outliers.ipynb
   * followed same steps as in the previous file
   * here I checked with ANOVA test which features do not play a role
   * encoded wine type
   * encoded quality type
   * dropped unnecessary columns
   * finded outliers and removed them
   * oversampled
   * tried Logistic Regression Method
   * tried Random Forest Model
   * tried KNN
   * I have followed the same logic in the creating of the other ML models:
3. File: wine+quality/ML- Quality Label Wine with outliers.ipynb
4. File: wine+quality/ML- Quality Label for Red Wine.ipynb
5. File: wine+quality/ML- Quality Label for White Wine part2.ipynb
6. File: wine+quality/ML- Quality Label for White Wine.ipynb
7. File: wine+quality/ML- Quality applying only on 6 Features.ipynb
# Part 4: EDA Findings and ML:
   * Presentation with all findings:
https://www.canva.com/design/DAF-ETIOGDk/yEwYAUx0yQ2cZD7hSRJnOA/edit?utm_content=DAF-ETIOGDk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
   * Presentation of the ML model which was chosen in the end:
https://www.canva.com/design/DAF_ecHsI8M/iecF7ccGR4y6GjpKyUBJKA/edit?utm_content=DAF_ecHsI8M&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
