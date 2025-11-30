# 📊 Gasoline Prices Increase: An Analytical Study
## CS 668 Capstone Project – Monica Hawkins
### Pace University, NY, USA

---

## 🎯 Introduction

Retail gasoline prices are primarily affected by:
- **Crude oil prices** (largest driver)
- **Available gasoline supply vs. demand**
- **Refinery operations and capacity**
- **Seasonal demand fluctuations** (spring/summer increases)

### Key Insight
> Prices rise when supply decreases relative to demand, and can fluctuate rapidly with disruptions in crude oil, refinery operations, or pipeline deliveries.

---

## 📋 Business Problem

### Seasonal Price Volatility Challenge
- Gasoline prices spike in spring/summer
- Heating oil demand increases in winter
- Prices can fluctuate despite stable crude oil

### Research Goal
Determine whether adjusting refinery operations based on seasonal patterns could help stabilize fuel costs and reduce price spikes.

---

## ❓ Research Questions

1. **What drives gasoline price changes?**
   - Identify key predictive factors

2. **How do seasonal trends affect pricing?**
   - Spring/summer vs. winter patterns

3. **Can we predict price increases?**
   - Build ML model for extreme price surges

---

## 📊 Data Sources & Preparation

### Primary Data Source
- U.S. Energy Information Administration (EIA)
- U.S. Natural Gas Prices dataset

### Data Features
| Aspect | Details |
|--------|---------|
| **Price Data** | Monthly (February - July) |
| **Categories** | 11 price categories |
| **Training Set** | 12 entries |
| **Test Set** | 3 entries |

### Data Challenges
- Missing values across multiple columns
- Mixed data types (object and float64) requiring conversion

---

## 🔬 Methodology

### Exploratory Data Analysis
- Data preprocessing & cleaning
- Missing value assessment
- Statistical descriptions (mean, std, min, max)

### Analysis Techniques
- Correlation analysis (heatmap visualization)
- Pairplot analysis for relationships
- Distribution analysis by category
- Categorical price comparisons

### Modeling Approach
- Machine learning model development
- Price prediction for extreme surges
- Seasonal trend forecasting

---

## 🔍 Key Findings

### Finding 1: Weak Linear Correlations
- Correlation between monthly prices (Feb, May, Jul) **< 0.4**
- Price in one month is **NOT** a strong predictor of another month
- Suggests external factors drive price changes, not just historical prices

### Finding 2: Category-Based Variation
- **TAD category** shows highest natural gas prices in February
- Significant price variation across 11 different categories
- Some categories show concentrated low-value prices; others have wide range

### Finding 3: Seasonal Price Distribution
- Prices vary widely across different categories
- Distribution patterns differ by month
- Outliers present in multiple categories

### Finding 4: Data Integrity
- Several columns have missing values requiring imputation
- Historical data availability varies by category

---

## 📈 Visual Insights

### Correlation Heatmap Results
- Weak relationships between monthly price points
- External factors likely more important than historical trends

### Distribution Analysis
- Wide variation in price ranges across categories
- Some categories show bimodal distributions
- Seasonal patterns evident in monthly comparisons

### Bar Chart Analysis
- TAD category dominates in February prices
- Pipeline-based categories show competitive pricing
- Import/export prices differ significantly

---

## ✅ Conclusion

### Key Takeaways
- Gasoline price increases driven primarily by **external supply/demand factors**, not historical prices
- **Seasonal trends** play a significant role in price volatility
- **Multiple categories and refinery operations** affect overall pricing

### Implications
- Refinery operations adjustments could help **stabilize seasonal prices**
- Predictive models must incorporate **external variables** (crude oil, supply, demand)
- **Strategic inventory management** during peak seasons could reduce price spikes

---

## 🚀 Next Steps

- [ ] Integrate crude oil price data
- [ ] Develop regression models with external variables
- [ ] Build time-series forecasting model
- [ ] Analyze impact of policy interventions
- [ ] Test predictions on future data

---

## 📞 Contact & Resources

**Author:** Monica Hawkins  
**University:** Pace University, New York, USA  
**Email:** mh21492p@pace.edu

**Dataset:** EIA U.S. Natural Gas & Gasoline Prices  
**Repository:** [Gasoline-Prices-Increase-CS-668-Capstone-Project](https://github.com/Mohawkins/Gasoline-Prices-Increase-CS-668-Capstone-Project)

---

**Questions?** Feel free to open an issue or contact the author.
