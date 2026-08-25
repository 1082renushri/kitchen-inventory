🍽️ Kitchen Inventory System

An AI-powered Kitchen Inventory System designed to reduce food wastage, prevent stock shortages, and support data-driven inventory decisions.

🚀 Overview

The system uses Random Forest Regression to predict future sales based on historical inventory and sales data. Based on the predicted demand, it estimates the stock required for the upcoming week and the investment needed for replenishment.

It also provides a dashboard for monitoring inventory, profit, seasonal trends, future purchase requirements, and stock alerts.

✨ Key Features
📊 Sales Prediction – Predicts upcoming sales using Random Forest Regression.
📦 Stock Planning – Calculates required stock for future replenishment.
💰 Purchase Estimation – Estimates the investment required for upcoming purchases.
📈 Product-wise Order Trends – The product page displays a line graph for each item, showing its order/sales trend over time.
📈 Dashboard – Provides profit analysis, seasonal trends, sales insights, and inventory status.
🚨 Stock Alerts – Detects when inventory reaches the defined threshold.
📱 SMS Notifications – Sends restocking alerts to suppliers using Twilio.
📄 PDF Reports – Generates weekly reports containing stock, predictions, profit, trends, and recommendations.
📧 Email Reports – Sends the generated reports to inventory managers weekly.


🛠️ Technology Stack
Python
Flask
Random Forest Regression
Pandas & NumPy
SQLite
Plotly
Twilio
ReportLab
