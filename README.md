# 🛒 Customer Shopping Behavior Analysis

## 📌 Overview

Built a retail analytics system to identify revenue drivers, high-value customer segments, and sales trends using Python and Power BI dashboards. This project analyzes retail shopping data to uncover customer purchasing behavior, product performance trends, and revenue-driving segments to support inventory planning and marketing decisions.

## 🧠 Business Problem

Retail companies need to understand:

- Which product categories generate the most revenue
- Which customer segments are most valuable
- What seasonal or behavioral trends affect sales

This project answers these questions using exploratory data analysis and visualization.

## 📂 Dataset

**Source:** [Kaggle - E-commerce Shopping Behavior Dataset](https://www.kaggle.com/datasets/)

**Records:** 5,500+ transactions

**Features:** 
- Customer ID, Age, Gender
- Product Category, Purchase Amount
- Date, Subscription Status
- Shipping Type, Review Rating

## 🛠 Tools & Technologies

- **Python 3.8+**
- **Pandas** - Data manipulation & analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualization
- **Jupyter Notebook** - Interactive analysis
- **Power BI** - Dashboard & business intelligence

## 🚀 How to Run

### Prerequisites
```bash
Python 3.8 or higher
pip (Python package manager)
```

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/Ashid332/Customer_shopping_behavior_Analysis.git
cd Customer_shopping_behavior_Analysis
```

2. **Create a virtual environment (optional but recommended):**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Open the notebook:**
```bash
jupyter notebook notebooks/customer_shopping_behavior.ipynb
```

5. **Run the analysis:**
   - Execute all cells in the notebook
   - The notebook will perform data cleaning, EDA, and generate visualizations
   - Results will be displayed inline

## 🔍 Workflow

1. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Remove duplicates
   - Data type conversions

2. **Exploratory Data Analysis (EDA)**
   - Statistical summaries
   - Distribution analysis
   - Correlation studies

3. **Customer Segmentation & Trend Analysis**
   - RFM analysis
   - Age-based segmentation
   - Category preference analysis

4. **Visualization of product & revenue trends**
   - Sales by category
   - Customer lifetime value patterns
   - Seasonal trends

5. **Business insight generation**
   - Key metric derivation
   - Actionable recommendations

6. **Dashboard creation in Power BI**
   - Interactive visualizations
   - KPI tracking
   - Business intelligence reports

## 📊 Key Insights

- **Top product categories contribute to 70%+ of total revenue** - Electronics and Clothing are major revenue drivers
- **High-value customer segments drive majority of repeat purchases** - Subscribers show 3x higher purchase frequency
- **Clear seasonal sales spikes during festival months** - December shows 45% higher sales
- **Strong correlation found between product type and purchase frequency** - Premium categories have longer purchase cycles
- **Subscription status significantly impacts revenue** - Subscribers have 2.5x average order value

## 📁 Project Structure

```
Customer_shopping_behavior_Analysis/
├── notebooks/
│   └── customer_shopping_behavior.ipynb    # Main analysis notebook
├── reports/
│   ├── Business Problem Document.pdf       # Project documentation
│   ├── Customer Shopping Behavior Analysis.pdf
│   └── Customer Shopping Behavior Analysis - Copy.pdf
├── dashboards/
│   └── customer_shopping_behavior_dashboard.pbix  # Power BI dashboard
├── requirements.txt                         # Python dependencies
├── LICENSE                                  # MIT License
└── README.md                               # This file
```

## 📈 Dashboard Preview

The Power BI dashboard tracks:
- Total customers and average spend
- Revenue & sales by product category
- Revenue & sales by age group
- Subscription impact on purchase behavior
- Shipping preference impact on revenue

## 🎯 Conclusion

This project provides actionable insights for retailers to optimize inventory planning, target high-value customers, and improve sales strategies. The combination of Python EDA and Power BI dashboards enables data-driven decision-making.

## 🚀 Business Expansion Ideas

- **Predict customer lifetime value (CLV)** - Build regression model to identify high-value customer acquisition targets
- **Build churn prediction models** - Use classification to identify at-risk customers
- **Develop recommendation engine** - Implement collaborative filtering for cross-selling

## 📌 Key Metrics Tracked

| Metric | Value | Insight |
|--------|-------|----------|
| Total Customers | 5,500+ | Large customer base |
| Revenue from Top 3 Categories | 70%+ | Concentrated revenue |
| Subscriber Purchase Frequency | 3x higher | Subscription value |
| Seasonal Peak (December) | +45% | Clear seasonality |

## 🔗 Author

**Ashidul Islam** | Junior Data Analyst

- Final Year BE in Electronics & Communication
- Open to Remote Analytics Roles
- [LinkedIn](https://www.linkedin.com/in/ashidulislam)

## 📄 License

MIT License - Feel free to use this project for educational and professional purposes.

---

**Built with ❤️ using Python, SQL, and Power BI**
