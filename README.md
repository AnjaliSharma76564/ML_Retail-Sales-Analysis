# 🛍️ Retail Sales Analysis

This machine learning project focuses on analyzing and forecasting retail sales using historical data from multiple stores. The dataset includes store-specific features, promotional details, and sales figures. The goal is to uncover business insights and build predictive models to improve sales performance and inventory planning.
## 📁 Folder Structure

- `notebooks/` – Contains the main Jupyter notebook for data exploration and model building.
- `data/` – Raw data files: features, stores, and sales.

## 📊 Datasets

- `features.csv.xls` – Store-level features (temperature, CPI, etc.).
- `stores.csv.xls` – Metadata for each store.
- `train.csv.xls` – Weekly sales data per store and department.

## 🧠 Objective

Build a machine learning model to predict weekly sales based on historical and store-level data.

## ▶️ How to Use

1. **Clone or download the repository**
   ```bash
   git clone  https://github.com/AnjaliSharma76564/ML_Retail-Sales-Analysis.git
   cd ML_Retail-Sales-Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open** `notebooks/ML_Retail_Sales_Analysis (3).ipynb` and run the cells in order.

## 🧰 Requirements

See `requirements.txt`.

## 📌 Notes

- Files are in `.xls` format — use `pd.read_excel()` to load them.


## 📄 License

MIT License
