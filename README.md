
---

# **PRODIGY_DS_03**
## *Classification of Bank Deposits using Decision Tree Model*

## *Table of Contents*
- [*Description*](#description)
- [*Overview*](#overview)
- [*Data Source*](#data-source)
- [*Installation*](#installation)
- [*Usage*](#usage)
- [*Data Preprocessing and Analysis*](#data-preprocessing-and-analysis)
- [*Model Building*](#model-building)
- [*Evaluation*](#evaluation)
- [*Contributors*](#contributors)
- [*Contributing*](#contributing)
- [*License*](#license)

---

## *Description*
*This project aims to predict whether a customer will subscribe to a term deposit using a **Decision Tree Classifier**. The dataset, sourced from a Portuguese bank, contains customer demographics and behavioral data. The objective is to identify key factors that influence a customer’s decision, optimizing marketing campaigns and increasing conversion rates.*

## *Overview*
*In this project, we analyze customer data from a Portuguese bank’s marketing campaign. The bank reached out to customers to promote its term deposit product, aiming to predict whether a customer would subscribe based on their profile. The project involves using **machine learning** to classify customers into two categories: those who subscribe to the term deposit ("yes") and those who do not ("no").*

*The key objectives of this project are:*
- *To predict customer subscription using a Decision Tree Classifier.*
- *To identify the most significant factors influencing the subscription decision.*
- *To optimize marketing strategies and improve customer targeting.*

## *Data Source*
*The dataset used in this project is sourced from a Portuguese bank’s marketing campaign. It contains demographic and behavioral attributes of customers, including:*
- *`Age`: Customer's age.*
- *`Job`: Type of job.*
- *`Marital Status`: Marital status of the customer.*
- *`Loan Status`: Whether the customer has a loan.*
- *`Contact Duration`: Duration of the phone call.*

*The target variable is `y`, indicating whether the customer subscribed to a term deposit ("yes" or "no").*

*Note: The dataset is publicly available from the UCI Machine Learning Repository or can be found in similar bank marketing campaign datasets.*


## *Installation*
```bash
git clone https://github.com/SnitTeshome/PRODIGY_DS_03
cd PRODIGY_DS_03
pip install -r requirements.txt
```

---

## *Usage*
*You can run the analysis by executing the provided Jupyter Notebook or Python scripts in this repository. Follow the steps in the notebook to preprocess the data, build the model, and evaluate its performance.*

---

## *Data Preprocessing and Analysis*
*The data preprocessing steps include:*
- *Handling missing values.*
- *Encoding categorical variables using **OrdinalEncoder** and **LabelEncoder**.*
- *Splitting the data into training and test sets.*
- *Exploratory Data Analysis (EDA) to examine feature distributions and correlations.*

*The analysis focuses on understanding the distribution of features and their relationship with the target variable (`y`).*

---

## *Model Building*
*We use a **Decision Tree Classifier** for classification. The steps involved are:*
- *Training the model on the preprocessed data.*
- *Performing hyperparameter tuning to optimize the model's performance.*
- *Evaluating the model using accuracy, confusion matrix, and classification report.*

---

## *Evaluation*
*The model’s performance is evaluated using:*
- *Accuracy score to measure the overall prediction accuracy.*
- *Confusion matrix to visualize true positives, false positives, true negatives, and false negatives.*
- *Classification report for detailed precision, recall, and F1-score.*

---

## *Contributors*
*This project was developed by Hanna, as part of the Data Science curriculum. Special thanks to mentors and peers for feedback and support during the development of this project.*

---

## *Contributing*
*We welcome contributions to enhance this project! If you would like to contribute:*
- *Fork the repository.*
- *Create a new branch (`feature/your-feature`).*
- *Commit your changes.*
- *Submit a pull request.*

*Make sure to align with the project's coding standards.*

---

## *License*
*This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.*

--- 
