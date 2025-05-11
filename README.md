# phase_3_project
# 📊 Predicting Customer Churn for SyriaTel

This project uses machine learning to predict customer churn for SyriaTel, a telecommunications company. The objective is to help SyriaTel proactively identify high-risk customers and reduce churn through data-driven retention strategies.

## 🔍 Problem Statement

Customer churn is a major challenge in the telecom industry. SyriaTel wants to understand:
- Which customers are likely to churn?
- What patterns or behaviors predict churn?
- How can the business intervene effectively?

## 🧠 Solution Approach

We used a supervised machine learning classification approach to build and evaluate models that can predict churn using customer data.

## 📁 Dataset

- Total records: 3,333
- Target: `Churn` (Yes/No)
- Features include:
  - Call minutes and charges (day, evening, night, international)
  - Customer service calls
  - Plan details (international plan, voicemail plan)
  - Account-level information (number of messages, total charges)

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## ⚙️ Modeling Workflow

1. **Data Cleaning & Preprocessing**
   - Encoded categorical variables
   - Scaled numerical features
   - Split into training and test sets

2. **Exploratory Data Analysis**
   - Visualized churn distribution
   - Explored correlations and feature distributions

3. **Model Training**
   - Trained and compared:
     - Logistic Regression
     - Decision Tree
   - Tuned hyperparameters using GridSearchCV

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix
   - ROC-AUC

## ✅ Best Model: Tuned Decision Tree

- **Accuracy**: ~93%
- **Recall for Churn**: ~70%
- Balanced performance and strong interpretability

## 🔍 Key Feature Insights

Top predictors of churn:
- `Total day minutes`
- `Customer service calls`
- `Total international minutes`
- `International plan`
- `Evening minutes and charges`

These patterns suggest that usage intensity, service experience, and plan choices drive churn behavior.

## 💡 Business Recommendations

- Monitor high-risk customers with frequent service calls or high usage
- Offer personalized retention deals to international users
- Create a dashboard to track churn predictions in real time
- Evaluate effectiveness of retention strategies using A/B testing

## 📈 Future Work

- Integrate satisfaction or payment history for better predictions
- Deploy the model as a web app or internal tool
- Monitor live model performance and retrain periodically

## 📂 Repository Structure

