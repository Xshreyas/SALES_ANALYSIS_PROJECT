# SALES_ANALYSIS_PROJECT

# 🧾 Sales Data Analysis using Python

## 📊 Overview
This project performs **data analysis on sales data** to extract valuable business insights such as top-selling products, popular cities, monthly sales trends, and frequently bought product combinations.  
It uses Python’s data analysis and visualization libraries to clean, process, and explore a large dataset of retail transactions.

---

## 🧠 Objectives
- Combine and clean multiple monthly sales data files into a single dataset.  
- Identify **best-selling products** and **top-performing cities**.  
- Analyze **monthly and hourly sales trends** to identify peak sales periods.  
- Discover **product combinations** often bought together using pair analysis.

---

## 🧰 Tech Stack
- **Language:** Python 🐍  
- **Libraries Used:**
  - `pandas` — for data cleaning, manipulation, and aggregation  
  - `numpy` — for numerical operations  
  - `matplotlib` — for visualizing trends and comparisons  
  - `itertools` & `collections.Counter` — for finding product combinations

---

## 📁 Project Structure
├── SalesAnalysis.ipynb # Main Jupyter Notebook for analysis
├── all_data_copy.csv # Combined dataset used in analysis
└── README.md # Project documentation (you’re reading it!)

yaml
Copy code

---

## ⚙️ Setup & Installation

### Prerequisites
Ensure you have Python 3.x installed. You can install required libraries using pip:

```bash
pip install pandas numpy matplotlib
Running the Project
Open the notebook file:

bash
Copy code
jupyter notebook SalesAnalysis.ipynb
Run all cells to reproduce the analysis and visualizations.

📈 Key Analyses Performed
Data Cleaning

Removed invalid headers and missing values.

Converted columns to appropriate data types (e.g., dates, floats).

Sales Trends

Monthly and hourly sales visualizations.

Geographical Insights

Top cities contributing to total sales.

Product Performance

Best-selling items based on total quantity and revenue.

Product Combination Analysis

Found pairs of items frequently bought together using combinations.

📊 Example Visualizations
Monthly Sales Bar Charts

Top Cities by Sales

Most Common Product Pairs
(All generated inside the Jupyter Notebook)

👨‍💻 Author
Shreyas Dhomase

📜 License
This project is licensed under the MIT License — you’re free to use and modify it with attribution.

💡 Future Enhancements
Automate the analysis for new monthly data uploads.

Add interactive dashboards using Plotly or Streamlit.

Integrate machine learning for sales forecasting.
