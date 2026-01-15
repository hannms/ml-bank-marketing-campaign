# ml-bank-marketing-campaign

End-to-end machine learning project to optimize bank deposit marketing campaign targeting.

## Project Overview
This project aims to support bank marketing teams in improving the effectiveness of **deposit marketing campaigns** using machine learning.  
By predicting the likelihood of customers subscribing to a term deposit, the model enables **prioritized targeting** instead of random outreach.

## Business Problem
Traditional deposit marketing campaigns often rely on broad or random customer targeting, leading to:
- Inefficient use of marketing resources  
- Low conversion effectiveness  
- High effort with limited impact  

The challenge is identifying **which customers should be prioritized** to maximize campaign success.

## Stakeholders
- Marketing team  
- Business decision makers  

## Project Objective
The objective of this project is to build a machine learning model that can:
- Predict customer subscription behavior (Yes / No)
- Improve campaign efficiency through targeted outreach
- Support data-driven decision making in marketing campaigns

## Dataset
- Dataset: Bank Marketing Campaign  
- Each row represents a customer interaction  
- Each column represents customer attributes, campaign information, and historical interaction data  

Target variable:
- `deposit` (Yes / No)

## Analytical Approach
1. Data Understanding  
2. Data Cleaning & Feature Engineering  
3. Machine Learning Modeling  
4. Model Evaluation using business-aligned metrics  

## Model Evaluation
The model is evaluated using:
- Recall
- Precision
- ROC-AUC
- Precision-Recall Curve
- Lift@TopN analysis  

These metrics are selected to align model performance with **marketing campaign objectives**.

## Business Impact
Compared to random targeting, the model enables marketing teams to:
- Focus on high-probability customers  
- Improve campaign efficiency  
- Reduce effort spent on low-potential segments  

## Conclusion
The machine learning model provides clear value as a **decision-support tool** for deposit marketing campaigns by improving targeting effectiveness and resource allocation.

## Recommendation
It is recommended to:
- Prioritize campaign execution on **Top-N customers** with the highest predicted probability  
- Use the model especially when marketing resources are limited  
- Periodically retrain the model to adapt to changing customer behavior  

## Repository Structure
├── Bank_Marketing_Campaign.ipynb
├── model.pkl
└── README.md

## How to Run
1. Open Bank_Marketing_Campaign.ipynb
2. Run all cells sequentially
3. Load the trained model using pickle if needed
