# Telecom Campaign Subscription — Exploratory Data Analysis

An exploratory data analysis project investigating which customer segments are most likely to subscribe to a telecom provider's new subscription package, based on a dataset of 41,180 customer records from a direct marketing campaign.

## Problem Statement

A telecom provider ran a marketing campaign but only 11.3% of 41,000 customers subscribed. This EDA identifies which customer segments are most responsive and what factors drive subscription decisions.

## Research Questions

- What are the main data quality issues and how were they addressed?
- How are key variables distributed and what patterns emerge?
- Which variables show the strongest relationship with subscription likelihood?
- Do macroeconomic conditions affect subscription behaviour?

## Key Findings

- Previous campaign success is the strongest predictor — customers who previously subscribed were **6x more likely** to subscribe again
- Call duration showed the strongest numeric correlation (r = 0.41)
- Macroeconomic indicators showed moderate negative correlations — customers are more receptive during economic uncertainty
- Chi-squared tests confirmed significant associations for previous campaign outcome, job type and contact method

## Dataset

41,180 records, 21 variables (10 numeric, 11 categorical) covering:
- Customer demographics
- Campaign contact details
- Macroeconomic indicators
- Subscription outcome (target variable)

Source: Moro et al. (2014) — UCI Bank Marketing Dataset

## Project Structure

- `EDA_Code.ipynb` — 
  Full analysis notebook
- `EDA_Report.docx` — 
  Project report

## Tech Stack

Python, pandas, numpy, matplotlib, seaborn, scipy

## Subject

36103 Statistical Thinking for Data Science  
Master of Data Science and Innovation  
University of Technology Sydney

## ⚠️ Academic Integrity

This project was completed as part of UTS 36103 assessment. 
Shared for portfolio purposes only. Please do not copy or submit any part of this work as your own.

## Author

Sushruta Gangadhar Patil  
Master of Data Science and Innovation  
University of Technology Sydney

Sushruta Gangadhar Patil  
Master of Data Science and Innovation  
University of Technology Sydney
