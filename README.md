# Churn Analysis Of a Telecom Firm

## Problem Statement

This dashboard created using PowerBI, can help the firm understand their customers better. It helps them to know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. 
By using data analytics and machine learning, it can predict which customers are at risk of leaving and understand the factors driving their decisions. This knowledge allows companies to take proactive steps to improve customer satisfaction.

- **DBMS:** mySQL 
= **Software for data visualization:** PowerBI
- **Language for ML:** Python

## Data Files

- **Customer_data.csv:** contains raw churn data.
- **vw_churndata:** contains the data where customer status is either churned or stay. To use for training the model.
- **vw_joindata:** contain the data where customer status is joined. It will be used for prediction.
- **Prediction_data.xlsx:** Excel sheet containing vw_churndata and vw_joindata to use in Python for performing predictions.
- **prediction.csv:** File containing the Customer Status (Churn or Stay) of the customers whose status is 'Join'.

## Steps:
- Data Transformation in mySQL. 
- Data Visualization using PowerBI.
- Prediction using RandomForestClassifer in Python.

## PowerBI dashboard:
- **SUMMARY DASHBOARD:**
![image](https://github.com/user-attachments/assets/954d4e8a-7e57-49f5-9fc6-36dd8b338acb)

-**PREDICTION DASHBOARD:**
![image](https://github.com/user-attachments/assets/0d0162ae-ecde-4904-8136-1020bc5c2054)
