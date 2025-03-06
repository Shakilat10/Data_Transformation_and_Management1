# Overview
This project includes performing data preparation, transformation, migration, and backup tasks using a retail e-commerce sales dataset. The goal is to analyze and manupulate the data,
integrate it into a non-relational database (MongoDB), and make data export, migration to the cloud smoothly, and backup processes.

# Objectives
Data Transformation: Clean and transform a messy dataset into a tidy format for further analysis.
Database Integration: Import data into NoSQL database (MongoDB) for correctly querying and storage.
Data Export and Backup: Export data from MongoDB, upload it to a Google Colab, and automate backup processes to ensure data security.

# Project Structure
The project is organized into two main tasks:
- Data Preparation and Database Integration: including data loading, cleaning, and transformation using Python.
  Database connection with MongoDB and data import and filtering and sorting records within the MongoDB database.
- Data Export, Migration, and Backup: Exporting data from MongoDB to local system then uploading exported data to cloud storage services like Google Colab.
  After that, automating cloud backups for data safety by using Google Drive.

## 📂 Dataset

- **Source**: Collected by Kaggle Website
- **Format**: CSV
- **Key Features**:
- Customer ID
- Gender
- Region
- Age
- Product Name
- Category
- Unit Price
- Quantity
- Total Price
- Shipping Fee
- Shipping Status
- Order Date
  
## 🔧 Technologies Used

- **Python** (Jupyter Notebook)
- **Libraries**:
- Data Manipulation: pandas, numpy
- Data Visualization: matplotlib, seaborn
- Database Management: pymongo (MongoDB)
- Cloud Storage & Back Up: google colab and google drive
