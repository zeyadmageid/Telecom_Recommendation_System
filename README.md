# Telecom Recommendation System - Grad School Data Science Project
![image](https://github.com/zeyadmageid/Telecom_Recommendation_System/assets/52506246/85eee40a-51f8-4af8-85d9-4522b38e702f)


# Overview 💡

Recommendation in the telecommunications sector involves proposing tailored offers to clients by analyzing their usage habits, demographic data, and pertinent variables. Delivering suggestions in the telecom field plays a vital role in enhancing customer contentment and bolstering revenue. Employing advanced algorithms and big data methods empowers telecom enterprises to supply pertinent and beneficial offers to customers, thereby fostering increased customer loyalty and sustained growth.

## What makes Offer Recommendation essential ❓
-  Enhance customer contentment: Offer recommendation enables telecom enterprises to gain deeper insights into their customers and offer pertinent, valuable incentives, ultimately resulting in heightened customer satisfaction.
-  Boost revenue: By delivering pertinent and beneficial offers to customers, telecom firms can augment their earnings through increased customer expenditures and diminished attrition.
-  Cultivate customer loyalty: Personalized offers from telecom companies create a superior customer experience, strengthening customer relationships and fostering heightened customer loyalty.

## Why Data Science ❓

Telecom companies possess extensive customer data, encompassing usage trends, billing records, and demographic particulars. Yet, they encounter challenges in harnessing this data to elevate customer contentment, loyalty, and revenue. The objective of the offer recommendation system is to leverage this data for proposing pertinent and beneficial incentives to customers, thereby driving up customer satisfaction and telecom company revenues.

Offer recommendation within the telecom sector is indispensable for enhancing customer satisfaction and bolstering revenue. Employing cutting-edge algorithms and big data methodologies, telecom enterprises can furnish customers with pertinent and valuable offers, culminating in heightened customer loyalty and sustained long-term growth.

## How to run the project ❓

-  Firstly run the 'EDA.ipnyb' notebook.
-  Secondly run the 'Recommendation_System.ipynb' notebook.

## Goals 🎯

-  Conduct problem-specific exploratory data analysis (EDA).
-  Comprehend the significance of offer recommendation and its role.
-  Develop an offer recommendation system tailored to a telecom company's needs.

## Data Overview:

The dataset was provided by a US-based telecom company and consists of information on 98,230 customers. It encompasses a total of 73 unique features that pertain to customer demographics, personal details, and usage patterns.


## Approach Summary:

In this project, we will construct a collaborative-filtering system centered on the user. To provide a simplified overview of our methodology:

-  We will develop an algorithm to identify, for a given customer (A), the n-most similar customers.
-  A churn-rate-based approach will be employed to determine, among these similar customers, which offer has been the most successful.
-  We will then select the most successful offer for our customer, A.

Our algorithm's training will be based on a subset of the dataset, specifically for customers who have received offers (labeled as A, B, C, D, E, F, G, H, I, or J) in their 'offer' field. The objective is to apply the findings to the 'No Offer' group.

This problem is treated as an unsupervised learning task. As a result, within this dataset, we lack a direct means to validate the correctness of our approach. In practice, the next step would involve testing this algorithm with real customers to assess its impact on reducing churn.
