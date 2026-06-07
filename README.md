# Supply Chain & Sales Forecasting Model (SupplyChain-ML)

## 📌 Project Overview
This project delivers an end-to-end data analysis and predictive modeling pipeline tailored for supply chain and inventory optimization. By utilizing Python and Machine Learning, the project processes **17,000+ detailed logical and financial records** to evaluate shipping behaviors, uncover revenue structures, and build a robust baseline for sales forecasting.

## 🛠️ Toolstack & Libraries
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning & Analytics:** Scikit-Learn (Linear Regression, Train-Test Split, Metrics)
- **Data Visualization:** Matplotlib, Seaborn

## 📊 Core Methodology & Project Steps

### 1. Data Pipeline & Local Architecture
- Structured a secure, localized data ingestion pipeline within Google Colab using Pandas.
- Handled specialized character encodings to guarantee data integrity across international logical records.
- Mapped raw features into core supply chain dimensions: `Sales`, `Order Quantity`, `Delivery Lead Time`, `Customer Count`, and `Orders Count`.

### 2. Exploratory Data Analysis (EDA) & Key Metrics
Evaluated key performance indicators (KPIs) critical to modern supply chain management:
- **Total Revenue Managed:** Over $3.5 Billion ($3,524,115,510.00).
- **Total Volume Processed:** 8.5+ Million orders delivering nearly 45 Million units.
- **Delivery Lead Time Analysis:** Extracted and audited average shipping lead times.
- **Statistical Insights:** Uncovered a weak correlation (**0.1310**) between bulk order quantity and total sales. This crucial insight proves that company top-line revenue is heavily driven by high-margin product categories rather than the sheer volume of low-value units.

### 3. Predictive Modeling (Machine Learning Forecasting)
- Isolated predictive features against the target revenue variable (`Sales`).
- Partitioned the historical dataset into **80% Training** and **20% Testing** subsets to validate generalization.
- Trained a **Linear Regression** forecasting model via `scikit-learn` to project upcoming sales trends based on current operational metrics.
- Evaluated performance using **Mean Absolute Error (MAE)** and the **R2 Score**, establishing an analytical framework for inventory risk management and demand planning.

## 📈 Key Visualizations
The model incorporates an advanced scatter plot tracking **Actual Sales vs. Machine Learning Predictions** against an ideal performance line, allowing logistics managers to quickly spot outlier transactions and pricing variations.

## 📁 Repository Structure
- `Supply_Chain_Sales_Forecasting.ipynb`: Complete Jupyter Notebook featuring step-by-step documentation, code cells, and output records.
- `Supply_Chain_Sales_Predictions.csv`: Tailored dataset output containing predictions mapped directly from the trained model.
- `README.md`: Professional project documentation.

## 💡 Business Value & Actionable Insights
This dashboard and model transition a business from backward-looking operational tracking to proactive revenue planning. Understanding that order volume doesn't linearly scale revenue helps inventory managers cut down on warehouse overhead, optimize safety stock levels, prevent costly stockouts, and negotiate sharper carriage terms based on accurate demand signals.
