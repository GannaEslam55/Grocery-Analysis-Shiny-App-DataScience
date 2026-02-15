# Grocery-Analysis-Shiny-App
📌 Project Overview

This project is an interactive Shiny Web Application built in R for analyzing grocery store data.
The application provides data visualization, customer segmentation using K-Means clustering, and market basket analysis using the Apriori algorithm.

It allows users to upload a CSV dataset and dynamically explore insights through interactive controls.

🚀 Features
📊 Data Visualization

Payment Type Distribution (Cash vs Credit)

Age vs Total Spending

Total Spending by City (Descending Order)

Distribution of Total Spending (Boxplot)

Combined View of All Plots

🤖 Machine Learning

K-Means Clustering

Clusters customers based on Age and Total Spending

User-controlled number of clusters (2–4)

🛍️ Market Basket Analysis

Association Rule Mining using the Apriori Algorithm

User-controlled:

Minimum Support

Minimum Confidence

🧠 Technologies Used

R

Shiny

arules

K-Means Clustering

Apriori Algorithm

📂 Dataset Requirements

The uploaded CSV file must include the following columns:

Column Name	Description
customer	Customer ID
age	Customer age
total	Total spending amount
city	Customer city
paymentType	Payment method (Cash/Credit)
⚙️ Installation & Running the App
1️⃣ Install Required Packages
install.packages("shiny")
install.packages("arules")

2️⃣ Run the Application
library(shiny)
runApp("app_directory_path")


Or simply open the project in RStudio and click Run App.

📈 Application Structure

UI
Handles layout, file upload, and user controls.

Server
Processes data, generates plots, performs clustering, and runs association rule mining.

🎯 Learning Outcomes

This project demonstrates:

Data preprocessing in R

Interactive web app development with Shiny

Exploratory Data Analysis (EDA)

Customer segmentation using K-Means

Association rule mining using Apriori
