# Customer Call List Data Cleaning & Transformation with Python

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)  
![Data](https://img.shields.io/badge/Data-Excel%2FCleaned-green?logo=microsoft-excel&logoColor=white)  

This repository contains a Python project for cleaning customer call data using pandas. It also includes a tutorial document covering essential pandas techniques for data wrangling and analysis.

## 📂 Project Structure

```
.
├── Data_Cleaning.ipynb         # Jupyter notebook with data cleaning workflow
├── Customer Call List.xlsx     # Raw dataset
├── Customer Call Cleaned List.xlsx # Cleaned dataset after processing
├── Pandas_Tutorial.docx        # Tutorial document on pandas
├── requirements.txt            # Python dependencies
└── README.md                   # Project overview and instructions
```

## 📝 Project Steps Followed
This project demonstrates how to:

- Load and inspect raw Excel data.
- Perform initial exploratory data analysis (EDA) to understand data quality issues.
- Remove duplicate records if any.
- Identify and handle missing values.
- Standardize and clean column data (e.g., phone numbers, names, standardizing date formats, splitting address into street, state, zipcode).
- Filter and sort data efficiently.
- Save the cleaned dataset to a new Excel file.

The included `Pandas_Tutorial.docx` provides additional guidance on pandas functionality such as filtering, sorting, grouping, and aggregation.

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:

- Python 3.8+
- pandas
- openpyxl (for reading/writing Excel files)
- Jupyter Notebook (optional, but recommended)

Install the dependencies using pip:
```bash
pip install -r requirements.txt
```

### Running the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/panditpooja/python-data-cleaning.git
   cd python-data-cleaning
   ```
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Data_Cleaning.ipynb` and run the cells step by step.

## 📖 Pandas Tutorial
The `Pandas_Tutorial.docx` file provides examples of common pandas operations, including:

- Display settings
- Filtering and sorting data
- Indexing with `.loc` and `.iloc`
- Grouping and aggregation with `.groupby()`

## 🙌 Acknowledgments
- Developed as part of a data cleaning practice exercise.
- Pandas library documentation: [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)

## ✍️ Author

**Pooja Pandit**  
Master’s Student in Information Science (Machine Learning)  
The University of Arizona  

[![GitHub](https://img.shields.io/badge/GitHub-panditpooja-black?logo=github)](https://github.com/panditpooja)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pooja--pandit-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pooja-pandit-177978135/)
