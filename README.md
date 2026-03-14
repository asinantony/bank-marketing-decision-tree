# Bank Marketing Prediction using Decision Tree

Python • Machine Learning • Scikit-Learn • Data Analysis

This project builds a **Machine Learning classification model** to predict whether a customer will subscribe to a **bank term deposit** based on marketing campaign data.

The model is implemented using **Decision Tree Classifier** from Scikit-Learn and demonstrates basic **data preprocessing, model training, and prediction** using Python.

---

## Project Overview

Banks run marketing campaigns to promote financial products such as term deposits.  
Predicting which customers are more likely to subscribe helps banks:

- Improve marketing efficiency
- Reduce operational cost
- Target the right customers

This project uses a **Decision Tree algorithm** to perform **binary classification**.

Target Variable:
y = 1 → Customer subscribed to term deposit
y = 0 → Customer did not subscribe

---

## Dataset

The dataset contains marketing campaign information for bank customers.

Dataset characteristics:

| Feature | Description |
|------|------|
| age | Customer age |
| job | Type of job |
| marital | Marital status |
| education | Education level |
| housing | Housing loan status |
| loan | Personal loan status |
| campaign | Number of contacts during campaign |
| pdays | Days since last contact |
| previous | Previous campaign contacts |
| emp.var.rate | Employment variation rate |
| cons.price.idx | Consumer price index |
| cons.conf.idx | Consumer confidence index |
| euribor3m | Euribor 3 month rate |
| nr.employed | Number of employees |

Dataset Size:
Rows: 41,188
Columns: 21

---

## Technologies Used

The project is implemented using the following tools and libraries:

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-Learn** – Machine Learning algorithms
- **Jupyter Notebook**

---

## Machine Learning Model

The model used in this project:
Decision Tree Classifier

Steps performed:

1. Import required Python libraries
2. Load dataset using Pandas
3. Clean dataset and remove missing values
4. Select important numerical features
5. Split dataset into training and testing sets
6. Train Decision Tree model
7. Predict outcomes on test dataset
8. Evaluate model performance

---

## Project Structure

```
bank-marketing-decision-tree
│
├── bank_marketing_prediction.ipynb   # Jupyter Notebook containing ML model
├── bank_marketing_dataset.csv       # Dataset used for training and testing
└── README.md                        # Project documentation
---

## Learning Outcomes

This project helped practice:

- Data loading and preprocessing
- Handling real-world datasets
- Feature selection
- Building classification models
- Machine learning using Scikit-Learn
- Data visualization using Matplotlib and Seaborn

---

## Possible Improvements

Future improvements for this project:

- Hyperparameter tuning for Decision Tree
- Try other models such as Random Forest
- Perform feature engineering
- Cross-validation for better evaluation
- Model comparison with other algorithms

---

## Author

**Asin Fraisiya**

BCA Data Analytics Graduate  
Aspiring Data Analyst / AI Analyst  

LinkedIn  
www.linkedin.com/in/asin-fraisiya-v-a-36694427a

---

## License

This project is created for learning and educational purposes.
