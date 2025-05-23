# 🚗 AWS QuickSight: Car Price Visualization with Carvana Dataset

This project uses data from **Carvana.com** (22,000+ cars) to analyze and visualize trends in **used car pricing** based on features like make, model, year, and mileage via **Amazon QuickSight**.

## 🔍 Project Overview

- 📊 Visualizes car price trends using Amazon QuickSight
- 📁 Data stored on Amazon S3 and linked using a manifest file
- 📈 Insights into how vehicle attributes affect market value

## 🛠️ Tools & Services

- **Amazon QuickSight (There is a free trial)**
- **Amazon S3** (for dataset storage)
- **QuickSight Manifest File** (for data import)

## 🧾 Dataset Details

- Source: [Kaggle - Carvana Car Prices](https://www.kaggle.com/datasets/ravishah1/carvana-predict-car-prices)
- ~22,000 listings with features like:
  - Make & Model
  - Year
  - Mileage
  - Price

## 🏃 Quick Start

Want to create the QuickSight dashboard locally? Here's how:

### Step 1: Get the Data & Manifest File

- Download the `.csv` dataset
- Download the `manifest.json` file (make sure to edit ‘BUCKET-NAME’ with the name of your S3 bucket when you create it)

### Step 2: Upload to Amazon S3

- Create an S3 bucket in your AWS account (any name of your choice, just make sure the manifest is updated to reflect it)
- Upload your CSV file & Manifest file


### Step 3: Load Data in QuickSight

- Go to Amazon QuickSight
- Choose **New dataset → S3**
- Link your manifest file
- Proceed to create a dataset and build visualizations

### Step 4: Build Your Dashboard

- Average price by car make/year
- Price vs. mileage trends
- Top-selling models by price range

## 📊 Visualization Example
<img width="1445" alt="Screenshot 2025-05-23 at 2 57 40 AM" src="https://github.com/user-attachments/assets/823cf562-9133-4307-8af3-462974a9ca28" />
