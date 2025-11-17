# 📊 Retail Sales Time Series Forecasting & ML Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Latest-orange.svg)](https://scikit-learn.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF.svg)](https://www.kaggle.com/)

## 🎯 Project Overview

Comprehensive time series analysis and machine learning forecasting on retail sales data (9,800+ records). This portfolio project demonstrates advanced data analytics skills including preprocessing, exploratory analysis, visualization, and predictive modeling using Random Forest algorithms.

## 🔑 Key Features

- **Data Preprocessing**: Date parsing, feature engineering (Year, Month, Quarter, Day, Week, Processing Days)
- **Statistical Analysis**: Descriptive statistics, category-wise performance metrics, regional analysis
- **Time Series Visualization**: Daily/monthly sales trends, seasonal patterns, quarterly performance
- **Correlation Analysis**: Feature relationships and business metric correlations
- **Machine Learning**: Random Forest Regressor for sales forecasting
- **Business Insights**: Data-driven recommendations and key findings

## 🛠️ Technologies & Tools

- **Programming**: Python 3.8+
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn (Random Forest)
- **Environment**: Kaggle Notebooks, Jupyter

## 📂 Dataset

**Source**: Superstore Sales Dataset (Kaggle)  
**Size**: 9,800 records, 18 columns  
**Features**: Order Date, Ship Date, Customer segments, Product categories, Sales, Region, Processing Days  
**Time Period**: Multi-year retail sales data

## 🔍 Methodology

### 1. Data Loading & Exploration
- Loaded 9,800 retail transaction records
- Examined data structure, types, and quality
- Assessed missing values and data integrity

### 2. Data Preprocessing
- Converted date columns with proper format handling
- Engineered temporal features (Year, Month, Quarter, DayOfWeek, WeekOfYear)
- Calculated business metrics (Processing Days)

### 3. Exploratory Data Analysis
- Statistical summaries by category, region, and sub-category
- Sales distribution analysis
- Temporal pattern identification

### 4. Time Series Analysis
- Daily and monthly sales trend visualization
- Seasonal pattern detection (Q4 peak performance)
- Year-over-year growth analysis

### 5. Machine Learning Forecasting
- **Model**: Random Forest Regressor (100 estimators)
- **Features**: Year, Month, Quarter, Day, DayOfWeek, Processing_Days
- **Split**: 80% training, 20% testing
- **Evaluation**: R² score, RMSE, MAE

### 6. Business Insights
- Category performance rankings
- Regional sales patterns
- Seasonal recommendations
- Predictive accuracy assessment

## 📊 Key Results

- **Total Sales**: $2,261,536.78
- **Average Order Value**: ~$230
- **Model Performance**: Evaluated via R² score and prediction error
- **Best Category**: Technology (highest sales)
- **Peak Season**: Q4 consistently shows highest performance
- **Top Sub-Categories**: Phones, Chairs, Storage, Tables

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/TejaVamshidharReddy/Retail-Sales-Time-Series-Forecasting.git
   cd Retail-Sales-Time-Series-Forecasting
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Run the notebook**
   - Open `retail-sales-forecasting-time-series-analysis.ipynb` in Jupyter or Kaggle
   - Execute cells sequentially

## 📈 Visualizations

The project includes multiple professional visualizations:
- Daily & Monthly sales trend lines
- Category performance bar charts
- Regional sales comparisons
- Seasonal quarterly patterns
- Correlation heatmaps
- ML model performance plots

## 💡 Business Recommendations

✅ Focus marketing on high-performing categories (Technology, Office Supplies)  
✅ Optimize inventory for Q4 seasonal peaks  
✅ Leverage ML forecasting for demand planning  
✅ Analyze regional differences for targeted strategies  
✅ Implement data-driven decision making

## 📁 Project Structure

```
Retail-Sales-Time-Series-Forecasting/
│
├── retail-sales-forecasting-time-series-analysis.ipynb  # Main notebook
├── README.md                                             # Project documentation
└── requirements.txt                                      # Python dependencies
```

## 🎓 Skills Demonstrated

- Data cleaning and preprocessing
- Feature engineering for time series
- Exploratory data analysis (EDA)
- Statistical analysis and interpretation
- Data visualization and storytelling
- Machine learning model development
- Model evaluation and validation
- Business insight generation
- Technical documentation

## 🔗 Links

- **Kaggle Notebook**: [View on Kaggle](https://www.kaggle.com/code/teju1021/retail-sales-forecasting-time-series-analysis)
- **Portfolio**: [GitHub Profile](https://github.com/TejaVamshidharReddy)

## 📝 License

This project is open source and available for educational and portfolio purposes.

## 👤 Author

**Chilukala Teja Vamshidhar Reddy**  
Data Scientist & ML Engineer  
📧 [GitHub](https://github.com/TejaVamshidharReddy)

---

⭐ If you found this project helpful, please consider giving it a star!
