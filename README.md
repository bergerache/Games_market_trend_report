# 🎮 Games Market Trend Analysis

**Market Research & Predictive Analytics | Python + Statistical Analysis**

*Strategic insights for video game industry decision-making through comprehensive data analysis*

![Analysis Overview](images/analysis-overview.png)

---

## 🎯 Business Problem & Solution

**Problem:** Video game companies need data-driven insights to optimize their platform strategies, genre investments, and regional market approaches for maximum ROI in 2017 and beyond.

**Solution:** Comprehensive market analysis of 16,444+ games across multiple platforms, genres, and regions to identify emerging trends, platform lifecycles, and regional preferences for strategic business planning.

## 👥 Target Audience

**Primary Stakeholders:**
- **Game Publishers** - Platform and genre investment decisions
- **Marketing Executives** - Regional strategy and resource allocation
- **Product Managers** - Portfolio optimization and trend forecasting
- **Business Analysts** - Market research and competitive intelligence

---

## 📊 **Data Analysis Overview**

🔗 **[View Complete Analysis →](https://nbviewer.org/github/bergerache/Games_market_trend_report/blob/main/Games_market_trendReport.ipynb)**

**Dataset Specifications:**
- **16,444 games** after data cleaning and validation
- **Multiple platforms** including PS2, X360, PS3, Wii, DS, and emerging consoles
- **Regional sales data** across North America, Europe, Japan, and other markets
- **Genre classification** and critical/user rating analysis
- **Time period:** Focus on modern gaming era (1995-2016) with 2017 predictions

---

## 📈 **Key Business Insights Generated**

### **Platform Strategy Intelligence**
- **Console Lifecycle Patterns**: Clear succession patterns (PS → PS2 → PS3) provide predictive framework for emerging platforms
- **2017 Platform Recommendations**: XOne, PS4, and WiiU identified as next-generation leaders based on release patterns
- **Sales Performance Leaders**: PS2 dominates with 1,233.56M sales, followed by X360 (961.24M) and PS3 (931.34M)

### **Genre Market Analysis**
- **Revenue Leaders**: Action genre leads with 1,150.64M total sales, followed by Sports (969.76M) and Shooter (648.99M)
- **Portfolio Optimization**: Action genre shows high variance with significant outliers, indicating both high-risk and high-reward potential
- **Strategic Focus**: Action and Sports genres recommended for primary advertising investment

### **Regional Market Intelligence**
- **Japan Market Specialty**: Role-Playing games dominate with 35.5% market share - significantly higher than other regions
- **North America Preferences**: Action (49.5%), Sports (52.1%), and Shooter (54.5%) genres show strong regional preference
- **Europe Market Balance**: More evenly distributed preferences across Action (30.6%), Sports (29.2%), and Shooter (31.8%)
- **Market Variance**: Japan shows highest genre preference variance (102.1) indicating specialized market, while NA (3.5) and EU (4.7) show more balanced preferences

### **Critical Success Factors**
- **Platform-Specific Correlations**: Critic scores correlation with sales varies significantly by platform (PS: 0.447, Wii: 0.178)
- **Regional Rating Impact**: Critic scores show strongest correlation with North America sales (0.24) compared to Japan (0.154) and Europe (0.221)
- **User vs Critic Preferences**: Statistical analysis reveals significant differences between platform user ratings (XOne: 6.5 vs PC: 7.1)

---

## 🛠️ **Technical Implementation**

### **Data Processing & Cleaning**
- **Data Quality**: Comprehensive cleaning of 16,715 initial records to 16,444 validated entries
- **Missing Value Treatment**: Strategic handling of critic scores (51.3% missing), user scores (40.1% missing), and ratings (40.5% missing)
- **Feature Engineering**: Creation of total_sales metric combining regional sales data
- **Data Type Optimization**: Conversion of year_of_release to datetime for temporal analysis

### **Statistical Analysis Methods**
- **Descriptive Statistics**: Platform and genre performance distributions
- **Correlation Analysis**: Relationship between critic scores, user ratings, and sales performance
- **Time Series Analysis**: Platform lifecycle and trend identification
- **Hypothesis Testing**: Statistical validation of platform and genre differences (t-tests, α=0.05)
- **Market Share Calculations**: Regional preference analysis and variance assessment

### **Visualization & Insights**
- **Distribution Analysis**: Temporal game release patterns and market evolution
- **Comparative Analysis**: Platform performance across regions and time periods
- **Box Plot Analysis**: Sales distribution variance across platforms and genres
- **Scatter Plot Analysis**: Correlation visualization between ratings and sales

---

## 📊 **Strategic Recommendations for 2017**

![Recommendations](images/strategic-recommendations.png)

### **Platform Investment Priority**
1. **Xbox One (XOne)** - 2013 release, following Xbox succession pattern
2. **PlayStation 4 (PS4)** - 2013 release, following PlayStation succession pattern  
3. **Wii U (WiiU)** - 2012 release, following Nintendo succession pattern

### **Genre Focus Strategy**
- **Primary Investment**: Action and Sports genres across all recommended platforms
- **Regional Specialization**: Consider Role-Playing games for Japan market expansion
- **Portfolio Balance**: Monitor Action genre volatility while leveraging its high revenue potential

### **Regional Market Approach**
- **Japan**: Specialize in Role-Playing games with targeted cultural content
- **North America**: Focus on Action, Sports, and Shooter genres with broad appeal
- **Europe**: Balanced portfolio approach across multiple genres

---

## 🧪 **Statistical Validation**

### **Hypothesis Testing Results**
- **Platform User Ratings**: Significant difference between XOne (6.5) and PC (7.1) user scores (p < 0.001)
- **Genre User Preferences**: Action (7.1) vs Sports (7.0) comparison shows minimal difference
- **Sample Sizes**: XOne (182 games), PC (752 games), Action (1,796 games), Sports (1,081 games)

### **Correlation Analysis**
- **Strongest Platform Correlation**: PlayStation platforms show highest critic-sales correlation (0.447)
- **Advertising Impact**: Inverse relationship between advertising effort and critic score importance
- **Regional Variations**: North America shows strongest critic score influence on sales

---

## 🚀 **Getting Started**

### **Prerequisites**
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
```

### **Data Access**
- **Dataset**: Video game sales data (games.csv)
- **Analysis Period**: 1995-2016 with 2017 predictions
- **Regions**: North America, Europe, Japan, Other markets

### **Running the Analysis**
1. **Clone the repository**
2. **Load the dataset**: `games = pd.read_csv('games.csv')`
3. **Execute data cleaning pipeline**
4. **Run statistical analysis and visualizations**
5. **Generate strategic recommendations**

---

## 🎯 **Skills Demonstrated**

### **Market Research & Analytics**
- ✅ **Trend Analysis**: Platform lifecycle identification and prediction
- ✅ **Market Segmentation**: Regional and demographic preference analysis
- ✅ **Competitive Intelligence**: Cross-platform and cross-genre performance comparison
- ✅ **Strategic Planning**: Data-driven recommendation framework

### **Statistical Analysis**
- ✅ **Hypothesis Testing**: T-tests for platform and genre comparisons
- ✅ **Correlation Analysis**: Relationship identification between multiple variables
- ✅ **Distribution Analysis**: Variance and outlier identification
- ✅ **Time Series Analysis**: Temporal pattern recognition and forecasting

### **Data Science & Visualization**
- ✅ **Data Cleaning**: Comprehensive missing value treatment and validation
- ✅ **Feature Engineering**: Calculated metrics and derived insights
- ✅ **Statistical Visualization**: Box plots, scatter plots, distribution analysis
- ✅ **Business Communication**: Clear presentation of complex analytical findings

### **Business Intelligence**
- ✅ **Market Analysis**: Multi-dimensional market assessment (platform, genre, region)
- ✅ **Predictive Analytics**: Trend-based forecasting for strategic planning
- ✅ **ROI Optimization**: Investment recommendation based on data insights
- ✅ **Strategic Communication**: Actionable recommendations for business stakeholders

---

## 📚 **Key Findings Summary**

### **Platform Evolution Insights**
- **Generational Patterns**: Clear succession models provide predictive framework
- **Market Concentration**: Top 6 platforms account for majority of market share
- **Emerging Opportunities**: Next-generation consoles show strong growth potential

### **Genre Market Dynamics**
- **Action Genre Leadership**: Highest revenue but high variance indicating risk/reward profile
- **Regional Specialization**: Japan's RPG preference vs Western action preferences
- **Advertising Strategy**: Genre-platform combinations require tailored approaches

### **Regional Market Characteristics**
- **Japan**: Specialized market with strong RPG preference and highest variance
- **North America**: Balanced high-engagement market across multiple genres
- **Europe**: Moderate engagement with distributed preferences

---

*Part of a comprehensive Business Intelligence Portfolio demonstrating market research and predictive analytics capabilities for strategic business decision-making.*
