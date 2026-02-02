# Employee Experience Analytics & Sentiment Modeling

## Objective
Analyze employee reviews to identify drivers of workplace dissatisfaction and build a predictive model to detect at-risk employees early.

## Dataset
Public employee reviews dataset (120k+ records) including:
- Structured ratings (work-life balance, growth, salary, satisfaction)
- Text feedback (likes/dislikes)

## Approach
1. Data cleaning & feature engineering
2. NLP sentiment analysis on review text
3. Exploratory analytics
4. Predictive modeling (Random Forest)
5. Model evaluation
6. Business recommendations

## Key Insights
- Career growth and work satisfaction were strongest drivers of low ratings
- Negative sentiment strongly correlated with dissatisfaction
- Model predicts dissatisfaction with 92% accuracy

## Model Performance
- Accuracy: 92%
- Recall (at-risk employees): 56%
- Precision: 64%

## Visualizations

### Correlation Heatmap
![heatmap](https://github.com/samathaa/employee-experience-analysis/blob/main/employee-experience-analytics/images/feature-importance.png)

### Sentiment by Rating
![sentiment](https://github.com/samathaa/employee-experience-analysis/blob/main/employee-experience-analytics/images/sentiment-plot.png)

### Feature Importance
![importance](https://github.com/samathaa/employee-experience-analysis/blob/main/employee-experience-analytics/images/feature-importance.png)

### Confusion Matrix
![confusion](https://github.com/samathaa/employee-experience-analysis/blob/main/employee-experience-analytics/images/confusion-matrix.png)

## Business Impact
This framework helps People Analytics teams:
- Identify dissatisfaction drivers
- Target retention efforts
- Improve employee experience
- Reduce attrition risk

## Tech Stack
Python, Pandas, Scikit-learn, NLP, Matplotlib, Seaborn

## How to Run
pip install -r requirements.txt  
Run notebook in notebooks/


