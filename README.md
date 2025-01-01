# Employee Performance Prediction

**INX Future Inc.**  
**Ritesh Kaushik**  
Email: [ritesh18043@gmail.com](mailto:ritesh18043@gmail.com)

---

## Project Summary
INX Future Inc. has observed declining employee performance, raising concerns among management. The CEO initiated a project to analyze employee data, identify the causes of performance issues, and develop solutions.

---

## Objectives
- Analyze department-wise performance.
- Identify the top 3 factors affecting employee performance.
- Develop a machine learning model to predict performance.
- Recommend strategies for improvement.

---

## Analysis
- The dataset is supervised, with ordinal and categorical variables.
- Key features include:
  - **Department**
  - **Job Role**
  - **Environment Satisfaction**
  - **Last Salary Hike**
  - **Work-Life Balance**
  - **Experience**
  - **Years with Current Manager**
- Techniques applied:
  - Correlation Coefficients
  - Label Encoding
  - Standardization
- Algorithms used for model training:
  - Logistic Regression
  - SVM
  - Decision Tree
  - Random Forest
  - Naive Bayes
  - KNN
  - XGBoost
  - ANN

---

## Steps Followed
1. Import and explore the dataset.
2. Perform department-wise analysis.
3. Encode categorical columns.
4. Calculate correlations and select key features.
5. Standardize data and split into train/test sets.
6. Train models, compare accuracy, and select the best.
7. Export the best model for future use.

---

## Results
- **Best Model**: Random Forest with GridSearchCV
- **Accuracy**: 93%

### Top 3 Features Affecting Performance:
1. **Environment Satisfaction**: 39.5%
2. **Last Salary Hike Percent**: 33.3%
3. **Years Since Last Promotion**: 16.7%

---

## Insights and Recommendations

### Insights:
- Improving environment satisfaction, salary hikes, and work-life balance boosts performance.
- Long tenure with the same manager negatively affects performance.

### Recommendations:
1. Enhance the work environment and salary growth.
2. Support work-life balance and consider role adjustments.
3. Implement job rotations and managerial shuffling to maintain engagement and growth.

---

