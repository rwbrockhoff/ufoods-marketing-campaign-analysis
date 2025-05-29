# UFood Marketing Campaign Analysis

## Business Case Context

This project analyzes a business case from UFood, Brazil's leading food delivery app operating in 1000+ cities. The company faces declining profit growth prospects and needs to optimize their marketing campaign performance to maintain market leadership.

**Business Challenge**: UFood's marketing department was tasked to spend their annual budget more wisely and prove the value of data-driven marketing decisions to skeptical stakeholders.

## Project Objectives

Following the case requirements, I conducted analysis to:

1. **Explore customer data** - Understand characteristic features of customer campaign response
2. **Customer segmentation** - Propose relevant customer segments
3. **Data visualization** - Create clear visualizations with written insights for both technical and business audiences
4. **Actionable recommendations** - Suggest data-driven actions to optimize campaign results

## Dataset Overview

- **Scope**: Several hundred thousand registered customers, serving ~1M consumers annually
- **Sample**: 2,240 customer records for analysis
- **Product Categories**: 5 major categories (wines, rare meats, exotic fruits, specialty fish, sweets)
- **Sales Channels**: Physical stores, catalogs, company website
- **Campaign Data**: 6 marketing campaigns tracking customer responses

## Technical Approach

**Tools**: Python, Pandas, Matplotlib, Seaborn

**Methods**:

- Exploratory data analysis with focus on customer campaign response characteristics
- Correlation analysis between demographics and campaign success
- Customer segmentation
- Channel performance comparison
- Visual storytelling for stakeholder presentation

## Key Findings

### Customer Segmentation Discovery

Through analysis, I identified distinct customer segments:

- **Family-Focused Buyers**: Married customers with children, moderate campaign engagement
- **Premium Enthusiasts**: Higher-income, fewer children, strong wine/specialty product preference
- **Catalog Loyalists**: Higher campaign acceptance, prefer traditional marketing channels
- **Digital Newcomers**: Web-focused, younger demographics

### Campaign Performance Insights

- Catalog marketing shows 8 percentage point advantage over digital channels
- Customer family size inversely correlates with campaign responsiveness
- Age groups 23-30 and 70+ demonstrate highest conversion potential (although smaller total population size)
- Wine purchases strongly correlate with overall campaign engagement

### Channel Optimization Opportunities

- **Catalog**: Highest conversion rates, underutilized potential
- **Web**: High volume, optimization opportunity exists
- **Store**: Steady performance, good for customer retention

## Business Recommendations

1. **Reallocate Marketing Budget**: Increase catalog marketing investment based on superior conversion rates
2. **Targeted Segmentation**: Focus premium campaigns on high-value segments (married, educated, fewer children)
3. **Age-Specific Messaging**: Develop tailored approaches for high-converting age brackets
4. **Cross-Channel Strategy**: Leverage catalog success to improve web/store campaign performance

## Technical Skills Demonstrated

- **Data Exploration**: Systematic analysis beyond basic statistics
- **Customer Segmentation**: Behavioral-based grouping methodology
- **Statistical Analysis**: Correlation identification and interpretation
- **Business Intelligence**: Translating data patterns into actionable strategies
- **Stakeholder Communication**: Technical findings presented for business audience

## Repository Structure

├── data/ # Original dataset and business case documentation
├── notebooks/ # Complete analysis workflow
├── outputs/figures/ # Business-ready visualizations
├── outputs/reports/ # Business-ready final report
└── README.md # Project documentation

## How to Run

1. Clone repository
2. Install requirements: `pip install -r requirements.txt`
3. Run notebook: `notebooks/u-food-marketing-data-analysis.ipynb`
