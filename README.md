# E-Commerce Sales Performance Analysis

## 📊 Project Overview
End-to-end data analysis project examining 9,994 sales transactions to identify profitability drivers, regional performance trends, and pricing strategy optimization opportunities.

## 🎯 Key Findings
- **Discount Strategy Crisis**: High discounts (20%+) resulted in -48% profit margin, destroying $125K in profit
- **Regional Disparity**: West region outperformed Central by 88% in profitability despite similar sales volumes
- **Category Issues**: Furniture category showed only 2.49% profit margin; Tables sub-category lost $17.7K
- **Technology = Winner**: 17.4% profit margin with Copiers and Phones as top performers
- **18.7% of transactions are unprofitable**, indicating urgent need for pricing review

## 🛠️ Technologies Used
- **Python**: Data cleaning, feature engineering, exploratory analysis
- **Pandas & NumPy**: Data manipulation and statistical analysis
- **Matplotlib & Seaborn**: Data visualization
- **Tableau Public**: Interactive dashboard creation
- **Git & GitHub**: Version control and documentation

## 📁 Project Structure
```
├── Sample - Superstore.csv          # Original dataset (9,994 records)
├── superstore_cleaned.csv           # Cleaned dataset with engineered features
├── superstore_analysis.ipynb        # Jupyter notebook with full analysis
├── superstore_analysis.png          # Python visualizations
└── README.md                        # Project documentation
```

## 📈 Analysis Process

### 1. Data Cleaning & Preparation
- Validated data quality (0 missing values across 9,994 records)
- Created calculated fields: Profit Margin, Revenue per Unit, Discount Categories
- Identified and analyzed 1,871 unprofitable transactions (18.7%)

### 2. Exploratory Data Analysis
- Regional performance comparison across 4 US regions
- Category and sub-category profitability analysis
- Discount impact assessment across 4 discount tiers
- Correlation analysis between discounts and profitability

### 3. Visualization & Dashboard
- Built interactive Tableau dashboard with 4 key visualizations
- Regional performance analysis
- Category profitability trends
- Discount strategy impact visualization
- Top/bottom performing sub-categories

## 🔗 Live Dashboard
**[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/srinivasa.rao.sammidi/viz/E-CommerceSalesPerformanceAnalysis_17696279951800/SalesPerformanceAnalysis)**

## 💡 Business Recommendations
1. **Implement discount cap at 10%** - Data shows discounts above 10% destroy profitability
2. **Investigate Central region operations** - Lowest profit margin (7.92%) needs cost structure review
3. **Re-evaluate furniture pricing** - Consider discontinuing Tables and Bookcases or adjust pricing strategy
4. **Increase technology inventory investment** - Highest margin category (17.4%) with strong demand
5. **Review all negative-profit transactions** - 18.7% of sales losing money requires immediate attention

## 📧 Contact
**Srinivasa Rao Sammidi**
- Email: sreenivas.sammidi@gmail.com
- LinkedIn: [linkedin.com/in/srinivasaraosammidi](https://linkedin.com/in/srinivasaraosammidi)
- GitHub: [@srinivasaraosammidi](https://github.com/srinivasaraosammidi)

---
*This project demonstrates end-to-end data analysis skills including data cleaning, exploratory analysis, visualization, and business insight generation.*
