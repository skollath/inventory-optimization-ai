# AI-Powered Inventory Optimization Platform

## Overview

This project demonstrates an end-to-end AI-driven inventory optimization platform designed to improve inventory planning, reduce stockouts, and optimize warehouse replenishment decisions.

The solution combines:

- Demand Forecasting
- Stockout Prediction
- Inventory Replenishment Planning
- Multi-Warehouse Optimization
- Tableau-Based Decision Dashboards

The goal is to transform inventory management from a reactive process into a proactive decision intelligence system.

---

## Business Problem

Retailers and supply chain organizations often face:

- Stockouts
- Excess inventory
- High transportation costs
- Poor inventory visibility
- Manual replenishment planning

Traditional forecasting models predict demand but do not recommend actions.

This project extends beyond forecasting by generating optimized replenishment recommendations.

---

## Solution Architecture

The workflow:

Historical Sales Data
→ Demand Forecasting
→ Stockout Prediction
→ Reorder Calculation
→ Warehouse Optimization
→ Tableau Dashboard

---

## Key Features

### Demand Forecasting

Uses Poisson-based machine learning models to estimate future product demand.

### Stockout Prediction

Calculates:

- Safety Stock
- Reorder Points
- Reorder Quantities

to identify inventory shortages before they occur.

### Warehouse Optimization

Uses IBM CPLEX and Docplex to determine:

- Optimal warehouse selection
- Shipment quantities
- Transportation cost minimization
- Lead-time optimization

### Decision Support Dashboard

Provides business users with actionable recommendations through Tableau.

---

## Technologies Used

### AI / Machine Learning

- Python
- Scikit-Learn
- Poisson Regression

### Optimization

- IBM CPLEX
- Docplex

### Data Engineering

- Pandas
- DuckDB

### Visualization

- Tableau

---

## Dataset Description 

The project uses approximately two years of transactional retail sales data (https://www.kaggle.com/datasets/akrambelha/global-e-commerce-dataset-1m-records-20242026) containing:

### Product Data

- Product ID
- Product Name
- Category
- Brand

### Sales Data

- Order Date
- Quantity
- Revenue
- Discounts

### Customer Data

- Loyalty Scores
- Customer Segments

### Fulfillment Data

- Warehouse Location
- Shipping Cost
- Delivery Time

---

## Repository Structure

forecasting_stockout_prediction/
optimization/
tableau/

---

## Future Enhancements

- Multi-store optimization
- Reinforcement learning
- Dynamic safety stock calculations
- Real-time inventory monitoring
- Quantum-inspired supply chain optimization
