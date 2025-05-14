# Titanic_Study

## Objective  
Predict passenger survival using demographic and ticket features (Accuracy: 82%).

## Key Features  
- Handled missing age values with median imputation  
- Engineered `Family_Size` feature from SibSp+Parch  
- Random Forest classifier with feature importance analysis  
- Achieved 82% accuracy on test set  

## Tech Stack  
`Python` `Pandas` `Scikit-learn` `Seaborn`

## Results  
 Accuracy: 82.1% on test set (Baseline: 61.5% if predicting all deaths)

Key Predictors:

Sex_male (24% importance) - Females had 74% survival vs 19% males

Fare (18%) - Top 25% fare payers had 55% survival vs 15% in lowest quartile

Age (16%) - Children (<10) had 59% survival rate


*Top predictors: Age, Fare, and Sex*

## Installation  
```bash
git clone https://github.com/yourusername/titanic-survival.git
pip install -r requirements.txt
