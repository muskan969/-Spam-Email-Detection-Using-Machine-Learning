# Spam Email Detection Using Machine Learning

## Project Overview
This project aims to detect spam emails using machine learning techniques. The system classifies emails as **spam** or **ham** (not spam) based on the email content.

## Dataset
- The dataset contains email messages and their corresponding labels (`Category`).
- Preprocessing steps handle text vectorization and label encoding for ML model input.

## Steps Performed
1. **Data Loading** – Upload CSV file and load into pandas DataFrame.
2. **Data Cleaning & Preprocessing** – Check missing values, encode labels, and vectorize text using TF-IDF.
3. **Exploratory Data Analysis (EDA)** – Visualize distribution of spam vs ham and analyze message lengths.
4. **Model Training** – Split data into training and testing sets and train classification models.
5. **Evaluation** – Check model accuracy and performance on test data.

## Technologies Used
- Python
- Jupyter Notebook / Google Colab
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
