# capstone-project Insurance claims

 Data Preparation
- Loaded CSV using `pandas`
- Removed missing values and duplicates
- Converted `incident_date` to datetime
- Visualized outliers in `total_claim_amount`

 Exploratory Data Analysis (EDA)
- Histograms and box plots of claim amounts
- Count plot of fraud vs non-fraud distribution
- Heatmap showing variable correlations
- Fraudulent claims tend to be higher in value and associated with specific patterns

 Statistical Analysis
- Conducted **t-test** to compare fraudulent vs non-fraudulent claim amounts  
  > Result: statistically significant difference (p < 0.05)

 Predictive Modeling
- Built a **Random Forest Classifier** to predict fraud  
- Used numerical variables, excluding policy ID  
- Achieved reasonable classification performance  
- Generated a classification report for evaluation

Key Insights
- Fraudulent claims average higher values  
- Certain incidents and customer attributes show stronger fraud correlation  
- Predictive model supports early fraud flagging strategies

 Reporting Tool
A PowerPoint presentation was developed to showcase:
- Project objectives
- Analytical findings
- Visualizations and trends
- Strategic recommendations

 Recommendations
- Tighten audits on high-value claims  
- Focus reviews on incident types with high fraud correlation  
- Incorporate ML model into claims screening workflow

 Future Work
- Add location-based external data  
- Explore seasonal or temporal trends  
- Deploy a live fraud detection dashboard

 Author
- Name: Sisanda Dlamini  
- Email: sisandamunkie79@gmail.com
- GitHub: (https://github.com/Sisanda79)


