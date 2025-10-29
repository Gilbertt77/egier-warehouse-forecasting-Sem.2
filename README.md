# Scientific Computing Project — EGIER Warehouse Forecasting

This repository contains my **Scientific Computing (Semester 2)** project.  
The project focuses on analyzing the **monthly bag production trend** of **EGIER**, an outdoor equipment manufacturer based in Bandung.  
The main goal is to predict **when the company needs to build a new warehouse** using computational modeling techniques.

## Project Description

This project applies key concepts from **numerical methods and scientific computing**:
- **Polynomial Regression (non-linear modeling)** for production trend analysis.  
- **Taylor Series approximation** to convert mathematical models into numerical form.  
- **Newton-Raphson method** to predict when the warehouse will reach full capacity.

The data represent **monthly production (M1–M144)** from **January 2018 to December 2023**.

## Project Tasks

### Problem 1 — Trend Modeling
Build a **non-linear polynomial model** (degree 3) to represent the production trend.  
Linear models are avoided to maintain higher accuracy.

### Problem 2 — Numerical Approximation
Convert the polynomial model into a **numerical function** using **Taylor Series** concepts.  
Evaluate the accuracy by comparing predicted and actual results.

### Problem 3 — Warehouse Capacity Forecast
Given the warehouse’s maximum capacity of **25,000 bags/month**, use **Newton-Raphson** root finding method to determine when production will exceed this limit.  
Include a 13 month preparation period for new warehouse construction.

### Problem 4 — Implementation
Provide a complete **Jupyter Notebook (.ipynb)** containing:
- Data visualization  
- Polynomial fitting  
- Taylor approximation  
- Root estimation via Newton Raphson

Google Colab link : https://colab.research.google.com/drive/1fvUT7-21qtkvGQ8Zi-T7u3FJhEuqf-eh?usp=sharing
