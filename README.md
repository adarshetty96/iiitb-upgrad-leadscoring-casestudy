# IIITB-UpGrad-LeadScoringCaseStudy

## **Overview**
This repository contains the Lead Scoring Case Study project, completed as part of the Post Graduate Diploma program in Data Science offered by IIIT Bangalore in collaboration with UpGrad.

The objective of this project is to build a machine learning model to predict the likelihood of leads converting into customers, enabling businesses to focus on high-potential leads.

---

## **Table of Contents**
1. [Problem Statement](#problem-statement)
2. [Objective](#objective)
3. [Data](#data)
4. [Approach](#approach)
5. [Results](#results)
6. [Technologies Used](#technologies-used)
7. [How to Run the Project](#how-to-run-the-project)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)

---

## **Problem Statement**
Businesses often struggle to identify which leads are most likely to convert into paying customers. This results in inefficiencies and wasted resources. This project aims to address this challenge by developing a predictive model for lead scoring.

---

## **Objective**
- Analyze and preprocess raw lead data.
- Build a machine learning pipeline to predict lead conversion probability.
- Evaluate the model's performance and provide actionable insights.

---

## **Data**
The dataset contains information about leads, including:
- **Lead Sources**: Website, referrals, etc.
- **Lead Activities**: Pages visited, time spent, etc.
- **Demographics**: Location, profession, etc.
- **Target Variable**: Whether the lead converted or not.

---

## **Approach**
1. **Exploratory Data Analysis (EDA)**:
   - Examined trends and patterns in the data.
   - Visualized correlations and distributions of features.
2. **Data Preprocessing**:
   - Handled missing values, used numerical/categorical encoding.
   - Normalized numeric variables.
3. **Model Building**:
   - Trained Logistic Rgression model 
   - Tuned hyperparameters using grid search.
4. **Model Evaluation**:
   - Used metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

---

## **Results**
- The best model achieved an **accuracy of 91%** and an **ROC-AUC score of ~96%**.
- Key insight:
  - Time spent on the website was a significant predictor of conversion.  

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Tools**: Jupyter Notebook, GitHub

---

## **How to Run the Project**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/adarshetty96/iiitb-upgrad-leadscoring-casestudy.git

2. **Navigate to the Directory**:
   ```bash
   cd iiitb-upgrad-leadscoring-casestudy
   ```
3. **Install Dependencies: Ensure you have Python installed. Install the required libraries**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Notebook: Open the LeadScoringCaseStudy.ipynb file in Jupyter Notebook or your preferred IDE.**

## **License**
This project is licensed under the MIT License.

## **Acknowledgments**
IIIT Bangalore and UpGrad for providing guidance and resources.
