# Hi, I'm Yumeng Cai

**MSc student in Data Analytics and Visualisation | Seeking Data Analyst Internship Opportunities in Singapore**

I am pursuing a **Master of Science in Data Analytics and Visualisation at Singapore University of Social Sciences**, with a current GPA of **4.75/5.0**.

My background spans product design, visual merchandising and UI design. I have used customer information and product sales data to inform product development and retail display decisions. I now build on that experience through Python analytics projects in customer segmentation, programme evaluation, price estimation and model monitoring.

[Email](mailto:yumeng055@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yumeng-cai-12a7363a4) · [Explore my repositories](https://github.com/yumeng-055?tab=repositories)

## Featured Analytics Projects

All five projects were completed independently as academic coursework. The repositories present analytical workflows, findings and business interpretations; proposed pilots and recommendations are distinguished from implemented outcomes.

### [Retail Customer Segmentation and Marketing Strategy](https://github.com/yumeng-055/retail-customer-segmentation)

**Question:** How can customer purchasing and channel patterns inform differentiated marketing?

- Analysed **2,000 customers**, prepared eight clustering features and retained five principal components explaining **81.57% of variance**
- Compared K-Means with Ward hierarchical clustering and retained **K-Means with K=4** as the final working segmentation; K=3 had stronger internal metrics, while K=4 distinguished family-focused grocery shoppers from high-income omnichannel shoppers
- Identified a fashion-and-technology segment representing **37.2% of customers**, with median monthly visits of **13 online and two in-store**
- Proposed segment-specific offers and a randomised pilot with defined conversion metrics

**Tools:** Python, pandas, scikit-learn, SciPy, PCA, K-Means, Ward clustering, Matplotlib, seaborn

### [Employee Training Effectiveness and Causal Analysis](https://github.com/yumeng-055/Employee-Training-Causal-Analysis)

**Question:** What evidence would support expanding a retail employee-training programme?

- Analysed **1,200 monthly observations across 50 stores**, comparing 25 trained and 25 control stores over 24 months
- Compared pooled OLS, fixed-effects and random-effects models, then estimated a two-way fixed-effects difference-in-differences model with store-clustered standard errors
- Estimated **+5.19 monthly sales units** under the required causal assumptions (**95% CI: 4.44–5.94**); the dataset does not establish a currency or monetary scale
- Recommended a controlled pilot and collection of training costs and margins before a broader rollout decision

**Tools:** Python, Pandas, Statsmodels, linearmodels, Difference-in-Differences

### [Singapore HDB Resale Price Analytics](https://github.com/yumeng-055/hdb-resale-price-analytics)

**Question:** How accurately can property characteristics estimate HDB resale prices?

- Prepared **25,073 transactions registered in 2025** and built reusable preprocessing and modelling Pipelines
- Compared Ridge, Random Forest and XGBoost using five-fold training cross-validation, fitting encoding and scaling within each training fold
- The selected XGBoost achieved a held-out **R² of 0.9596** and **MAE of SGD 28,600**
- Built a **Streamlit estimation prototype** and analysed errors by town to identify segments needing further review

**Tools:** Python, Pandas, Scikit-learn, XGBoost, Streamlit

### [Airline Customer Experience & Model Performance Monitoring](https://github.com/yumeng-055/airline-customer-experience-monitoring)

**Question:** When does a satisfaction model become less reliable, and what evidence should guide investigation and retraining?

- Prepared **20,000 historical survey rows and three monthly batches of 3,000 rows**, with fold-local preprocessing and a frozen classification model
- Tracked monthly **F1 declining from 0.9475 to 0.9028**, separating data-quality warnings, input drift and performance alerts
- Diagnosed **Business-class recall falling from 91.5% to 79.1%**, using passenger-group errors and PSI to prioritise investigation
- Built reproducible local monitoring reports and evaluated a retrospective challenger, with future-batch validation required before any proposed model replacement

**Tools:** Python, Pandas, Scikit-learn, Random Forest, PSI, Matplotlib, Seaborn

### [Singapore Temperature Forecasting](https://github.com/yumeng-055/Singapore-Temperature-Forecasting)

**Question:** Does rainfall improve annual temperature forecasts enough to justify a more complex model?

- Analysed **65 annual observations from 1960–2024**, using a ten-year chronological holdout
- Compared SES, ARIMA and rainfall-assisted ARIMAX; SES achieved **RMSE of 0.4735°C**, nearly identical to ARIMA
- Found that ARIMAX did not improve this holdout comparison, even with observed holdout rainfall supplied
- Documented forecast limitations and proposed rolling-origin evaluation before operational use

**Tools:** Python, Pandas, Statsmodels, Matplotlib

## From Retail and Design to Analytics

My professional experience provides context for the questions I explore in these projects:

- **Customer and sales analysis:** Reviewed customer profiles and previous-quarter product sales to inform category selection and design direction for sports merchandise
- **Product delivery:** Independently designed a collection spanning **six product categories**, coordinating supplier discussions, prototyping and sample approval through production
- **Retail execution:** Designed display schemes, produced merchandising guidelines and managed display-prop distribution for **up to approximately 100 stores**
- **Communication and collaboration:** Worked with operations teams, product managers, suppliers and front-end developers to turn requirements into practical deliverables

## Skills

| Area | Tools and methods |
| --- | --- |
| Python analytics | Pandas, NumPy, Scikit-learn, Statsmodels, linearmodels |
| Data preparation | Schema and identity checks, missing-value treatment, categorical encoding, scaling, feature engineering, fold-local Pipelines |
| Statistical analysis | Hypothesis testing, confidence intervals, OLS, panel data, fixed and random effects, difference-in-differences, cluster-robust standard errors |
| Machine learning | Logistic regression, Ridge, Random Forest, XGBoost, PCA, K-Means, hierarchical clustering |
| Time series forecasting | SES, ARIMA, ARIMAX, chronological holdout evaluation, residual diagnostics and prediction intervals |
| Model evaluation | Cross-validation, hyperparameter search, OOF threshold selection, permutation importance, group-level error analysis |
| Model monitoring | Batch data-quality checks, PSI, precision/recall and F1 tracking, retrospective challenger evaluation, retraining and rollback planning |
| Business and customer analytics | Customer profiling, marketing recommendations, KPI definitions, experiment planning and decision briefs |
| Visualisation and applications | Matplotlib, Seaborn, Streamlit estimation prototypes |
| SQL and BI tools | SQL queries, joins, aggregations and window functions; Excel; Tableau; DBeaver |
| Reproducible development | Modular Python, command-line reporting, Jupyter, unittest, Git/GitHub |
| Design background | Figma, Adobe Illustrator, Photoshop, Rhino, KeyShot |

## Education and Interests

**Singapore University of Social Sciences**  
Master of Science in Data Analytics and Visualisation · Jan 2026 – Jun 2027  
Current GPA: 4.75/5.0

**University of Electronic Science and Technology of China, Zhongshan Institute**  
Bachelor of Engineering in Industrial Design · Sep 2013 – Jun 2017

I am interested in **customer analytics, marketing analytics and retail business intelligence**, with a focus on connecting analytical evidence to business decisions.

**For internship enquiries:** [yumeng055@gmail.com](mailto:yumeng055@gmail.com)
