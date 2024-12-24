
# Data Quality App

**Data Quality App** is a Python-based web application built with Streamlit to perform data quality tasks, such as handling missing values, duplicates, and outliers in datasets. The app provides an intuitive interface for data preprocessing, cleaning, visualization.

## Features

### 1. Data Quality Analysis
- **Dataset Upload**: Supports CSV and Excel files.
- **Dataset Information**: View detailed dataset info, including memory usage and data types.
- **Missing Values**: Detect and handle missing values with multiple options.
- **Duplicates**: Identify and remove duplicate rows.
- **Outliers**: Detect and handle outliers using IQR or Z-Score.

### 2. Data Visualization
- Interactive plots: Bar plots, pie charts, histograms, scatter plots, and more.
- Correlation heatmaps: Visualize relationships between features.
- Customizable color palettes for enhanced visuals.

### 4. Data Modification
- Convert column data types.

### 5. Download Cleaned Data
- Save the modified dataset to your system for further use.

---

## Prerequisites
- Python 3.12 or higher.
- Streamlit and other required libraries (see `requirements.txt`).

---

Installation
Clone the repository (optional)

git clone https://github.com/yasminehosny/Data_Quality.git
cd Data_Quality_app
Create a virtual environment

python -m venv venv
Activate the virtual environment

On Windows:

venv\Scripts\activate
On macOS/Linux:

source venv/bin/activate
Install the required dependencies

pip install -r requirements.txt
Alternatively, install the required libraries manually:

pip install streamlit pandas scikit-learn matplotlib seaborn missingno imbalanced-learn

Verify the installed libraries

pip list
Run the Streamlit app

The app will open in your default web browser.


Usage
Upload your dataset (CSV or Excel) via the sidebar.
Select the task you want to perform from the navigation menu in the sidebar:
Dataset Info: View detailed information about your dataset (columns, types, non-null counts).
Describe Dataset: View the descriptive statistics of the dataset.
Handle Missing Values: Choose to fill or drop missing values from columns.
Handle Duplicates: Identify and remove duplicate rows.
Handle Outliers: Remove outliers using the IQR method.
Download Modified Dataset
After performing any changes, you can download the modified dataset by clicking the download button on the sidebar.


