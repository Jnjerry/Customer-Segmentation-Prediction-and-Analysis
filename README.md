# Customer-Segmentation-Prediction-and-Analysis

# Problem Statement 
To be able to optimize a marketing strategy by understanding customer behavior and segmenting the customer base effectively. The data to be used contains various customer attributes such as InvoiceNo, StockCode, Description,Quantity, InvoiceDate,UnitPrice, CustomerID and Country. 
## Goal
The goal of this project is to apply a clustering algorithm to identify distinct customer segments based on their purchasing attributes. By doing so, we intend to gain actionable insights into customer behavior, tailor marketing campaigns for specific segments, improve customer engagement, and ultimately increase overall revenue.

The output is to be used for a one off campaign and therefore there was no need to deploy the solution in a production environment.

## Tools: Python, JupyterNotebook,Github and PowerBI

<img width="328" alt="image" src="https://github.com/Jnjerry/Customer-Segmentation-Prediction-and-Analysis/assets/19590985/cd0e72f5-d743-42ec-a023-2277a590a40f">

## Data Cleaning
- Dropped rows without customer IDs(These cannot be imputed)
- Dropped Duplicates

## Feature Engineering
- Drop the Description column
- Feature generation to have the following features
<img width="464" alt="image" src="https://github.com/Jnjerry/Customer-Segmentation-Prediction-and-Analysis/assets/19590985/2157d9d8-609f-4c9f-8b9e-f3cea066c841">
 
## Feature Scaling

## Segmentation using DBSCAN(Results)
![image](https://github.com/Jnjerry/Customer-Segmentation-Prediction-and-Analysis/assets/19590985/170b76d8-bfb6-41eb-8b86-601b3aaf8ca6)
---
![image](https://github.com/Jnjerry/Customer-Segmentation-Prediction-and-Analysis/assets/19590985/cf661301-db8c-4c60-8ccf-8df12cfc9ee4) 

![image](https://github.com/Jnjerry/Customer-Segmentation-Prediction-and-Analysis/assets/19590985/724698d6-6a1c-405e-916a-60cc0ff4c382)







