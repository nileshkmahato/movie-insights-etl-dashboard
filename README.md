# 🎬 Movie Insights ETL Dashboard

This project implements a full ETL (Extract, Transform, Load) pipeline for analyzing and visualizing movie data. Using **Python**, **pandas**, and **Streamlit**, this dashboard fetches movie data from an API, cleans it, and displays insights via interactive charts. It can be deployed in just a few steps to **Streamlit Cloud**.

---

## 🚀 Features

- **Extract**: Fetch movie data from an API (OMDb or TMDb).
- **Transform**: Clean and manipulate data with pandas, including feature engineering and aggregation.
- **Load**: Save processed data to a CSV or SQLite database.
- **Dashboard**: Visualize insights using Streamlit, with charts for genre distribution, ratings over time, and top actors.

---
---
## API 
1. https://www.omdbapi.com/
2. https://developer.themoviedb.org/docs/getting-started
---

## 🛠️ Setup Instructions

### **1. Environment Setup**

Start by setting up your Python environment. Make sure you have `pip` installed, then install the required libraries:

```bash
pip install pandas requests streamlit sqlite3
python -m venv venv